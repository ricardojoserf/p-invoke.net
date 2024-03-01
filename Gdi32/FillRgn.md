## FillRgn

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool FillRgn(
   IntPtr hdc,
   IntPtr hrgn,
   IntPtr hbr
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-fillrgn)
