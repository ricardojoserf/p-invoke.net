## GetThemeBackgroundExtent

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeBackgroundExtent(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   ref RECT pContentRect,
   out RECT pExtentRect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemebackgroundextent)
