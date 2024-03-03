## InvertRgn

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool InvertRgn(
   IntPtr hdc,
   IntPtr hrgn
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-invertrgn)
