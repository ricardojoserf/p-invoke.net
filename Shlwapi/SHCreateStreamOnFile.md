## SHCreateStreamOnFile

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int SHCreateStreamOnFile(
   [MarshalAs(UnmanagedType.LPWStr)] string pszFile,
   STGM dwMode,
   out IStream ppstm
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-shcreatestreamonfilew)
