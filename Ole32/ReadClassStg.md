## ReadClassStg

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int ReadClassStg(
   IStorage pStg,
   out Guid pclsid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-readclassstg)
