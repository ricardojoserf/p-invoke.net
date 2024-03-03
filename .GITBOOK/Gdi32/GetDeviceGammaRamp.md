## GetDeviceGammaRamp

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetDeviceGammaRamp(
   IntPtr hdc,
   [Out] RAMP lpRamp
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getdevicegammaramp)
