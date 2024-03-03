## GetOutlineTextMetrics

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetOutlineTextMetrics(
   IntPtr hdc,
   uint cbData,
   ref OUTLINETEXTMETRIC lpOTM
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getoutlinetextmetricsa)
