## OpenThemeFile

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern IntPtr OpenThemeFile(
   [MarshalAs(UnmanagedType.LPWStr)] string pszThemeFile,
   [MarshalAs(UnmanagedType.LPWStr)] string pszColorScheme,
   [MarshalAs(UnmanagedType.LPWStr)] string pszSizeName
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/office/vba/api/powerpoint.application.openthemefile)
