## RegConnectRegistry

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegConnectRegistry(
   string lpMachineName,
   uint hKey,
   out IntPtr phkResult
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regconnectregistryw)
