## PatBlt

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PatBlt(
   IntPtr hdc,
   int nXLeft,
   int nYLeft,
   int nWidth,
   int nHeight,
   uint dwRop
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-patblt)
