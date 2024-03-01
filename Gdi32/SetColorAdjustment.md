## SetColorAdjustment

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetColorAdjustment(
   IntPtr hdc,
   [In] ref COLORADJUSTMENT lpca
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setcoloradjustment)
