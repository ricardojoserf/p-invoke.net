## EnumEnhMetaFile

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool EnumEnhMetaFile(
   IntPtr hdc,
   IntPtr hemf,
   EnhMetaFileProc lpEnhMetaFunc,
   IntPtr param,
   [In] ref RECT lpRect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-enumenhmetafile)
