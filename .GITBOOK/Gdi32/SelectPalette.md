## SelectPalette

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr SelectPalette(
   IntPtr hdc,
   IntPtr hpal,
   bool bForceBkgd
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-selectpalette)
