## GetAspectRatioFilterEx

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetAspectRatioFilterEx(
   IntPtr hdc,
   out SIZE lpAspectRatio
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getaspectratiofilterex)
