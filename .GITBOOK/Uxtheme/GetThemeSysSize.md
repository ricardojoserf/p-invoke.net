## GetThemeSysSize

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeSysSize(
   IntPtr hTheme,
   int iSizeId,
   out int piSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemesyssize)
