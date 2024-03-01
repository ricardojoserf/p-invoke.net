## StgOpenStorageEx

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgOpenStorageEx(
   [MarshalAs(UnmanagedType.LPWStr)] string pwcsName,
   uint grfMode,
   uint stgfmt,
   uint grfAttrs,
   ref STGOPTIONS pStgOptions,
   IntPtr reserved,
   ref Guid riid,
   out IStorage ppObjectOpen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-stgopenstorageex)
