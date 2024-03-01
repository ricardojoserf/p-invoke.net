## AnimatePalette

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool AnimatePalette(
   IntPtr hPal,
   uint iStartIndex,
   uint cEntries,
   [MarshalAs(UnmanagedType.LPArray)] PALETTEENTRY[] ppe
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-animatepalette)
