## GetEnhMetaFileHeader

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetEnhMetaFileHeader(
   IntPtr hemf,
   uint cbBuffer,
   ref ENHMETAHEADER lpEnhMetaHeader
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getenhmetafileheader)
