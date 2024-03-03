## GetThemeTextMetrics

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeTextMetrics(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   out TEXTMETRIC ptm
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemetextmetrics)
