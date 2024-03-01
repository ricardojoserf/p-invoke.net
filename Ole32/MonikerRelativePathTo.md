## MonikerRelativePathTo

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int MonikerRelativePathTo(
   IMoniker pmkSrc,
   IMoniker pmkDest,
   out IMoniker ppmkRelPath,
   [MarshalAs(UnmanagedType.Bool)] out bool pdwReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/objidl/nf-objidl-monikerrelativepathto)
