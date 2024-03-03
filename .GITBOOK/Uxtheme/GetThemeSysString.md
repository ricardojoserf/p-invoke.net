## GetThemeSysString

```csharp
[DllImport("uxtheme.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern HRESULT GetThemeSysString(
   IntPtr hTheme,
   int iStringId,
   StringBuilder pszStringBuff,
   int cchMaxStringChars
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemesysstring)
