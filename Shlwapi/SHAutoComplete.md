## SHAutoComplete

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int SHAutoComplete(
   IntPtr hwndEdit,
   SHACF dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-shautocomplete)
