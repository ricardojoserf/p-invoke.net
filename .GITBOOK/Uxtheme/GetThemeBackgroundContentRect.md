## GetThemeBackgroundContentRect

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeBackgroundContentRect(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   ref RECT pBoundingRect,
   out RECT pContentRect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemebackgroundcontentrect)
