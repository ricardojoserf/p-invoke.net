## LookupPrivilegeName

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LookupPrivilegeName(
   string lpSystemName,
   IntPtr lpLuid,
   StringBuilder lpName,
   ref uint cbName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegenamea)
