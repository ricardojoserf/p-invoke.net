## StgCreateDocfile

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgCreateDocfile(
   [MarshalAs(UnmanagedType.LPWStr)] string pwcsName,
   uint grfMode,
   uint reserved,
   out IStorage ppstgOpen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-stgcreatedocfile)
