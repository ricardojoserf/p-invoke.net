## DwmUpdateThumbnailProperties

```csharp
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmUpdateThumbnailProperties(
   IntPtr hThumbnailId,
   ref DWM_THUMBNAIL_PROPERTIES ptnProperties
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmupdatethumbnailproperties)
