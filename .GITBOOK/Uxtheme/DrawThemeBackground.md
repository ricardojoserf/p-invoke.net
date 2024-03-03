## DrawThemeBackground

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT DrawThemeBackground(
   IntPtr hTheme,
   HDC hdc,
   int iPartId,
   int iStateId,
   ref RECT pRect,
   ref RECT pClipRect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-drawthemebackground)
