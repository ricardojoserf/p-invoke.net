## RegQueryInfoKey

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegQueryInfoKey(
   IntPtr hKey,
   StringBuilder lpClass,
   ref uint lpcClass,
   IntPtr lpReserved,
   IntPtr lpcSubKeys,
   IntPtr lpcMaxSubKeyLen,
   IntPtr lpcMaxClassLen,
   IntPtr lpcValues,
   IntPtr lpcMaxValueNameLen,
   IntPtr lpcMaxValueLen,
   IntPtr lpcbSecurityDescriptor,
   IntPtr lpftLastWriteTime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryinfokeya)
