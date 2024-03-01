## GetThemeFont

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeFont(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   int iPropId,
   ref LOGFONT pFont
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemefont)
