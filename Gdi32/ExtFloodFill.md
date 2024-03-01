## ExtFloodFill

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool ExtFloodFill(
   IntPtr hdc,
   int nXStart,
   int nYStart,
   uint crColor,
   uint wFillType
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-extfloodfill)
