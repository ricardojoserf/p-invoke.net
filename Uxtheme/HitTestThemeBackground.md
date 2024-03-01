## HitTestThemeBackground

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT HitTestThemeBackground(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   uint dwOptions,
   ref RECT pRect,
   IntPtr hrgn,
   POINT ptTest,
   out HITTESTCODE pHitTestCode
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-hittestthemebackground)
