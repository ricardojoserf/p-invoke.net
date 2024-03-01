## SetTextJustification

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetTextJustification(
   IntPtr hdc,
   int nBreakExtra,
   int nBreakCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-settextjustification)
