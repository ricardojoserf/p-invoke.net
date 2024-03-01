## CreateEnhMetaFile

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreateEnhMetaFile(
   IntPtr hdc,
   string lpFilename,
   [In] ref RECT lpRect,
   string lpDescription
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createenhmetafile)
