## GetThemePosition

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemePosition(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   int iPropId,
   out POINT pPoint
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemeposition)
