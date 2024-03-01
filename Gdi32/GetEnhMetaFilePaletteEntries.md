## GetEnhMetaFilePaletteEntries

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetEnhMetaFilePaletteEntries(
   IntPtr hemf,
   uint cEntries,
   [Out] uint[] lpPaletteEntries
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getenhmetafilepaletteentries)
