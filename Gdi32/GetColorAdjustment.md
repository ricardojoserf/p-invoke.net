## GetColorAdjustment

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetColorAdjustment(
   IntPtr hdc,
   out COLORADJUSTMENT lpca
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcoloradjustment)
