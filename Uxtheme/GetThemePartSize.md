## GetThemePartSize

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemePartSize(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   ref RECT prc,
   int eSize,
   out SIZE psz
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemepartsize)
