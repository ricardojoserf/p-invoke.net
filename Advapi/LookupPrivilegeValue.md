## LookupPrivilegeValue

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LookupPrivilegeValue(
   string lpSystemName,
   string lpName,
   ref LUID lpLuid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegevaluea)
