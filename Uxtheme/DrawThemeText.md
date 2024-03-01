## DrawThemeText

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT DrawThemeText(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszText,
   int cchText,
   uint dwTextFlags,
   uint dwTextFlags2,
   ref RECT pRect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-drawthemetext)
