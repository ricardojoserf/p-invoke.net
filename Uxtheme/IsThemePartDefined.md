## IsThemePartDefined

```csharp
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern bool IsThemePartDefined(
   IntPtr hTheme,
   int iPartId,
   int iStateId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-isthemepartdefined)
