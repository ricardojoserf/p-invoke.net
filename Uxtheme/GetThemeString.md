## GetThemeString

```
[DllImport("uxtheme.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern HRESULT GetThemeString(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   int iPropId,
   StringBuilder pszBuff,
   int cchMaxBuffChars
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemestring)
