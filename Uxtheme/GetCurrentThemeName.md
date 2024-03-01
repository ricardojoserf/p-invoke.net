## GetCurrentThemeName

```
[DllImport("uxtheme.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern HRESULT GetCurrentThemeName(
   StringBuilder pszThemeFileName,
   int cchMaxNameChars,
   StringBuilder pszColorBuff,
   int cchMaxColorChars,
   StringBuilder pszSizeBuff,
   int cchMaxSizeChars
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getcurrentthemename)
