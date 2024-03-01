## SetDIBColorTable

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint SetDIBColorTable(
   IntPtr hdc,
   uint iStart,
   uint cEntries,
   [In] RGBQUAD[] pColors
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setdibcolortable)
