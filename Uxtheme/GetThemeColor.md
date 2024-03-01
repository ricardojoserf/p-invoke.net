## GetThemeColor

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeColor(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   int iPropId,
   out COLORREF pColor
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemecolor)
