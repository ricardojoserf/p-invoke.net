## SetPaletteEntries

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint SetPaletteEntries(
   IntPtr hpal,
   uint iStart,
   uint cEntries,
   [In] PALETTEENTRY[] pPalEntries
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setpaletteentries)
