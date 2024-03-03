## GetThemeIntList

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeIntList(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   int iPropId,
   out INTLIST pIntList
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemeintlist)
