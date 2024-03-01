## GetTextExtentExPoint

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetTextExtentExPoint(
   IntPtr hdc,
   string lpszString,
   int cchString,
   int nMaxExtent,
   [Out] int[] lpnFit,
   [Out] int[] alpDx,
   ref SIZE lpSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gettextextentexpointa)
