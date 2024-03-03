## SHCreateDirectoryEx

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHCreateDirectoryEx(
   IntPtr hwnd,
   string pszPath,
   ref SECURITY_ATTRIBUTES psa
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shcreatedirectoryexw)
