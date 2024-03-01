## DrawThemeIcon

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT DrawThemeIcon(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   ref RECT pRect,
   HIMAGELIST himl,
   int iImageIndex
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-drawthemeicon)
