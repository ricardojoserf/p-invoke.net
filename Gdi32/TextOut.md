## TextOut

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool TextOut(
   IntPtr hdc,
   int x,
   int y,
   string lpString,
   int c
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-textouta)
