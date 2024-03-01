## IsThemeBackgroundPartiallyTransparent

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT IsThemeBackgroundPartiallyTransparent(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   out bool pfIsTransparent
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-isthemebackgroundpartiallytransparent)
