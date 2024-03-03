## RegCreateKeyEx

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegCreateKeyEx(
   IntPtr hKey,
   string lpSubKey,
   uint Reserved,
   string lpClass,
   uint dwOptions,
   uint samDesired,
   IntPtr lpSecurityAttributes,
   out IntPtr phkResult,
   out uint lpdwDisposition
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcreatekeyexa)
