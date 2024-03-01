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

Microsoft documentation: (TODO)
