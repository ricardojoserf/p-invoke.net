## SetSystemVisualStyle

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern void SetSystemVisualStyle(
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszFilename,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszColor,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-setsystemvisualstyle)
