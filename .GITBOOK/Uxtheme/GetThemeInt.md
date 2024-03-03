## GetThemeInt

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeInt(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   int iPropId,
   out int piVal
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemeint)
