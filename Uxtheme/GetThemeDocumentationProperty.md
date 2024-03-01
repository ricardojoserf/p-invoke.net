## GetThemeDocumentationProperty

```
[DllImport("uxtheme.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern HRESULT GetThemeDocumentationProperty(
   [MarshalAs(UnmanagedType.LPWStr)] string pszThemeName,
   [MarshalAs(UnmanagedType.LPWStr)] string pszPropertyName,
   StringBuilder pszValueBuff,
   int cchMaxValChars
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemedocumentationproperty)
