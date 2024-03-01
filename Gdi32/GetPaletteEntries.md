## GetPaletteEntries

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetPaletteEntries(
   IntPtr hpal,
   uint iStartIndex,
   uint nEntries,
   [Out] PALETTEENTRY[] lppe
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getpaletteentries)
