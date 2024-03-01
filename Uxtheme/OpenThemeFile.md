## OpenThemeFile

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern IntPtr OpenThemeFile(
   [MarshalAs(UnmanagedType.LPWStr)] string pszThemeFile,
   [MarshalAs(UnmanagedType.LPWStr)] string pszColorScheme,
   [MarshalAs(UnmanagedType.LPWStr)] string pszSizeName
);
```

Microsoft documentation: (TODO)
