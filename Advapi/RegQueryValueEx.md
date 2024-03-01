## RegQueryValueEx

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegQueryValueEx(
   IntPtr hKey,
   string lpValueName,
   IntPtr lpReserved,
   IntPtr lpType,
   IntPtr lpData,
   ref uint lpcbData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryvalueexa)
