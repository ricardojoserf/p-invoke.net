## AngleArc

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool AngleArc(
   IntPtr hdc,
   int x,
   int y,
   uint r,
   float StartAngle,
   float SweepAngle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-anglearc)
