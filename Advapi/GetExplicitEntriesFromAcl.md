## GetExplicitEntriesFromAcl

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetExplicitEntriesFromAcl(
   IntPtr pAcl,
   out uint pcCountOfExplicitEntries,
   out EXPLICIT_ACCESS[] pListOfExplicitEntries
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getexplicitentriesfromacla)
