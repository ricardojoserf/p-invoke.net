## SHQueryRecycleBin

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHQueryRecycleBin(
   string pszRootPath,
   ref SHQUERYRBINFO pSHQueryRBInfo
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shqueryrecyclebinw)
