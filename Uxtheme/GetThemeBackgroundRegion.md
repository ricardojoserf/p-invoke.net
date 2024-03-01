## GetThemeBackgroundRegion

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeBackgroundRegion(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   ref RECT pRect,
   out IntPtr pRegion
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemebackgroundregion)
