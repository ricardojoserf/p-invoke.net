## StgOpenAsyncDocfileOnIFillLockBytes

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgOpenAsyncDocfileOnIFillLockBytes(
   IFillLockBytes pflb,
   uint grfMode,
   uint reserved,
   out IStorage ppstgOpen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-stgopenasyncdocfileonifilllockbytes)
