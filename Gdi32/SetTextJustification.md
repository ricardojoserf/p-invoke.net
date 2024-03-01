## SetTextJustification

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetTextJustification(
   IntPtr hdc,
   int nBreakExtra,
   int nBreakCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-settextjustification)
