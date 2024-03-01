## SetEntriesInAcl

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint SetEntriesInAcl(
   uint cCountOfExplicitEntries,
   ref EXPLICIT_ACCESS pListOfExplicitEntries,
   IntPtr OldAcl,
   out IntPtr NewAcl
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setentriesinacla)
