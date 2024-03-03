## DwmQueryThumbnailSourceSize

```csharp
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmQueryThumbnailSourceSize(
   IntPtr hThumbnail,
   out SIZE size
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmquerythumbnailsourcesize)
