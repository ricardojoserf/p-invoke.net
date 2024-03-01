## GetThemeTransitionDuration

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeTransitionDuration(
   IntPtr hTheme,
   int iPartId,
   int iStateIdFrom,
   int iStateIdTo,
   int iPropId,
   out int pdwDuration
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemetransitionduration)
