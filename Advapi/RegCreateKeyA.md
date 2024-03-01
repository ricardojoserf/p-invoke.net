## RegCreateKeyA

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegCreateKeyA(
   IntPtr hKey,
   string lpSubKey,
   out IntPtr phkResult
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcreatekeya)
