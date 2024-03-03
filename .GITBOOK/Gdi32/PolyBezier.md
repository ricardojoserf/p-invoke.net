## PolyBezier

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PolyBezier(
   IntPtr hdc,
   [In] POINT[] lppt,
   uint cPoints
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-polybezier)
