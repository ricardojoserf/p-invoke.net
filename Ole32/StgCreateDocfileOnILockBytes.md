## StgCreateDocfileOnILockBytes

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgCreateDocfileOnILockBytes(
   ILockBytes plkbyt,
   uint grfMode,
   uint reserved,
   out IStorage ppstgOpen
);
```

Microsoft documentation: (TODO)
