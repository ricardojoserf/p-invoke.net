## GetClassFile

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int GetClassFile(
   string szFilename,
   out Guid pclsid
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-getclassfile)
