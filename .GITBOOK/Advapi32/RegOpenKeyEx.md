## RegOpenKeyEx

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegOpenKeyEx(
   IntPtr hKey,
   string lpSubKey,
   uint ulOptions,
   uint samDesired,
   out IntPtr phkResult
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopenkeyexa)
