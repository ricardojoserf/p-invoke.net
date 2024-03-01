## DrawThemeTextEx

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT DrawThemeTextEx(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszText,
   int cchText,
   uint dwTextFlags,
   ref RECT pRect,
   ref DTTOPTS pOptions
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-drawthemetextex)
