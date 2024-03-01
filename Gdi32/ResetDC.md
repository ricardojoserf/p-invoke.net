## ResetDC

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr ResetDC(
   IntPtr hdc,
   [In] ref DEVMODE lpdm
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-resetdca)
