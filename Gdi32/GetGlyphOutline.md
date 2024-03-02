## GetGlyphOutline

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetGlyphOutline(
   IntPtr hdc,
   uint uChar,
   uint fuFormat,
   out GLYPHMETRICS lpgm,
   uint cbBuffer,
   IntPtr lpvBuffer,
   ref MAT2 lpmat2
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getglyphoutlinea)
