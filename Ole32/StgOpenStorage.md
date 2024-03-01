## StgOpenStorage

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgOpenStorage(
   [MarshalAs(
   UnmanagedType.LPWStr)] string pwcsName,
   IStorage pstgPriority,
   uint grfMode,
   IntPtr snbExclude,
   uint reserved,
   out IStorage ppstgOpen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-stgopenstorage)
