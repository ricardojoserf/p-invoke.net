## RegQueryInfoKey

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RegQueryInfoKey(
   IntPtr hKey,
   string lpClass,
   ref int lpcbClass,
   IntPtr lpReserved,
   ref int lpcSubKeys,
   ref int lpcbMaxSubKeyLen,
   ref int lpcbMaxClassLen,
   ref int lpcValues,
   ref int lpcbMaxValueNameLen,
   ref int lpcbMaxValueLen,
   ref int lpcbSecurityDescriptor,
   ref FILETIME lpftLastWriteTime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryinfokeyw)
