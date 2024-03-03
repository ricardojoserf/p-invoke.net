## GetThemePropertyOrigin

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemePropertyOrigin(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   int iPropId,
   out PROPERTYORIGIN pOrigin
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemepropertyorigin)
