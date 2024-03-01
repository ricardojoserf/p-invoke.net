## SHCreateItemFromParsingName

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHCreateItemFromParsingName(
   string pszPath,
   IntPtr pbc,
   ref Guid riid,
   out IntPtr ppv
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromparsingname)
