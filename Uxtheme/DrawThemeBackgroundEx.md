## DrawThemeBackgroundEx

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT DrawThemeBackgroundEx(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   ref RECT pRect,
   ref DTBGOPTS pOptions
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-drawthemebackgroundex)
