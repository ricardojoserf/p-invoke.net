## DwmRegisterThumbnail

```csharp
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmRegisterThumbnail(
   IntPtr hwndDestination,
   IntPtr hwndSource,
   out IntPtr phThumbnailId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmregisterthumbnail)
