## GetThemeBool

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeBool(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   int iPropId,
   out BOOL pfVal
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemebool)
