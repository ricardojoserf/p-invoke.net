## SetWindowThemeAttribute

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT SetWindowThemeAttribute(
   HWND hwnd,
   WINDOWTHEMEATTRIBUTETYPE eAttribute,
   IntPtr pvAttribute,
   uint cbAttribute
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-setwindowthemeattribute)
