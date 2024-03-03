## SHEmptyRecycleBin

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHEmptyRecycleBin(
   IntPtr hwnd,
   string pszRootPath,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shemptyrecyclebinw)
