## CheckColorsInGamut

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool CheckColorsInGamut(
   IntPtr hdc,
   IntPtr lpRGBTriples,
   IntPtr lpBuffer,
   uint nCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-checkcolorsingamut)
