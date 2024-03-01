## DrawThemeEdge

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT DrawThemeEdge(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   ref RECT pDestRect,
   uint uEdge,
   uint uFlags,
   out RECT pContentRect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-drawthemeedge)
