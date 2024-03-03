## SetWindowTheme

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT SetWindowTheme(
   HWND hwnd,
   [MarshalAs(UnmanagedType.LPWStr)] string pszSubAppName,
   [MarshalAs(UnmanagedType.LPWStr)] string pszSubIdList
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-setwindowtheme)
