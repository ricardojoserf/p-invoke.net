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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-stgcreatedocfile)
