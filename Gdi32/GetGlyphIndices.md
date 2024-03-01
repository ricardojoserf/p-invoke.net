## GetGlyphIndices

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetGlyphIndices(
   IntPtr hdc,
   string lpstr,
   int c,
   [Out] ushort[] pgi,
   uint fl
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getglyphindicesa)
