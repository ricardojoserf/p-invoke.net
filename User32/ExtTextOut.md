## ExtTextOut

```
[DllImport("gdi32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ExtTextOutA(IntPtr hdc,
   int X,
   int Y,
   uint fuOptions,
   [In] ref RECT lprc,
   string lpString,
   uint cbCount,
   [In] int[] lpDx
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-exttextouta)
