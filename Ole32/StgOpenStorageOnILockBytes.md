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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-stgopenstorageonilockbytes)
