## GetFontData

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetFontData(
   IntPtr hdc,
   uint dwTable,
   uint dwOffset,
   [Out] byte[] lpvBuffer,
   uint cbData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getfontdata)
