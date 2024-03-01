## SHCreateStreamOnFileEx

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int SHCreateStreamOnFileEx(
   [MarshalAs(UnmanagedType.LPWStr)] string pszFile,
   STGM grfMode,
   uint dwAttributes,
   bool fCreate,
   IStream pstmTemplate,
   out IStream ppstm
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-shcreatestreamonfileex)
