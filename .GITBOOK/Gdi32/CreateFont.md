## CreateFont

```csharp
[DllImport("gdi32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern IntPtr CreateFont(
   int nHeight,
   int nWidth,
   int nEscapement,
   int nOrientation,
   int fnWeight,
   uint fdwItalic,
   uint fdwUnderline,
   uint fdwStrikeOut,
   uint fdwCharSet,
   uint fdwOutputPrecision,
   uint fdwClipPrecision,
   uint fdwQuality,
   uint fdwPitchAndFamily,
   string lpszFace
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createfonta)
