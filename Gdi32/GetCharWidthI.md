## GetCharWidthI

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetCharWidthI(
   IntPtr hdc,
   uint giFirst,
   uint cgi,
   [In] IntPtr pgi,
   [Out] int[] lpBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharwidthia)
