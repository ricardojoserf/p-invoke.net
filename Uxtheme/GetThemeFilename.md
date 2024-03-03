## GetThemeFilename

```csharp
[DllImport("uxtheme.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern HRESULT GetThemeFilename(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   int iPropId,
   StringBuilder pszThemeFileName,
   int cchMaxBuffChars
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemefilename)
