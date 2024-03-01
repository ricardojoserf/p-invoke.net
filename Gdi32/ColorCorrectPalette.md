## ColorCorrectPalette

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool ColorCorrectPalette(
   IntPtr hdc,
   IntPtr hpal,
   uint deFirstEntry,
   uint numEntries,
   uint deFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-colorcorrectpalette)
