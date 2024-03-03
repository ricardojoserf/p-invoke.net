## RegDeleteKeyEx

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegDeleteKeyEx(
   IntPtr hKey,
   string lpSubKey,
   uint samDesired,
   uint Reserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeyexa)
