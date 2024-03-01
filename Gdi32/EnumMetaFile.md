## EnumMetaFile

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool EnumMetaFile(
   IntPtr hdc,
   IntPtr hmf,
   MetaFileProc proc,
   IntPtr param
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-enummetafile)
