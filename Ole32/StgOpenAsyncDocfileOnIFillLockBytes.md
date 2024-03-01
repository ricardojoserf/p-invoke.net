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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/propsys/nf-propsys-stgopenasyncdocfileonifilllockbytes)
