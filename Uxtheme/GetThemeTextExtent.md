## GetThemeTextExtent

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeTextExtent(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   [MarshalAs(UnmanagedType.LPWStr)] string pszText,
   int cchCharCount,
   uint dwTextFlags,
   ref RECT pBoundingRect,
   out RECT pExtentRect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemetextextent)
