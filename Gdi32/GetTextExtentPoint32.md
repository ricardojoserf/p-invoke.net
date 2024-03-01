## GetTextExtentPoint32

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetTextExtentPoint32(
   IntPtr hdc,
   string lpString,
   int c,
   out SIZE psizl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gettextextentpoint32a)
