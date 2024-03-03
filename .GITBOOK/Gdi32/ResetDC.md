## ResetDC

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr ResetDC(
   IntPtr hdc,
   [In] ref DEVMODE lpdm
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-resetdca)
