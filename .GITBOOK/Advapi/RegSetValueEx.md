## RegSetValueEx

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegSetValueEx(
   IntPtr hKey,
   string lpValueName,
   uint Reserved,
   uint dwType,
   byte[] lpData,
   uint cbData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regsetvalueexa)
