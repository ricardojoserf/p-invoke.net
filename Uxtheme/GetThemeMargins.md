## GetThemeMargins

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeMargins(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   int iPropId,
   ref RECT prc,
   out MARGINS pMargins
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthememargins)
