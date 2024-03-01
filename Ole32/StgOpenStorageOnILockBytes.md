## StgOpenStorageOnILockBytes

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgOpenStorageOnILockBytes(
   ILockBytes plkbyt,
   IStorage pStgPriority,
   uint grfMode,
   IntPtr snbExclude,
   uint reserved,
   out IStorage ppstgOpen
);
```

Microsoft documentation: (TODO)
