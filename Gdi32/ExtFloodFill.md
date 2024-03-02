## ExtFloodFill

```
[DllImport("gdi32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ExtFloodFill(
   IntPtr hdc,
   int nXStart,
   int nYStart,
   uint crColor,
   uint fuFillType
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-extfloodfill)
