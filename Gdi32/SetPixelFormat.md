## SetPixelFormat

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetPixelFormat(
   IntPtr hdc,
   int iPixelFormat,
   [In] ref PIXELFORMATDESCRIPTOR ppfd
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setpixelformat)
