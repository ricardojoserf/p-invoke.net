## RegEnumValue

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegEnumValue(
   IntPtr hKey,
   uint dwIndex,
   StringBuilder lpValueName,
   ref uint lpcchValueName,
   IntPtr lpReserved,
   IntPtr lpType,
   IntPtr lpData,
   IntPtr lpcbData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regenumvaluea)
