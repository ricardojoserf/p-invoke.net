## OpenThemeData

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern IntPtr OpenThemeData(
   HWND hwnd,
   [MarshalAs(UnmanagedType.LPWStr)] string pszClassList
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-openthemedata)
