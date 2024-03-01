## OleCreate

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreate(
   Guid rclsid,
   Guid riid,
   uint renderopt,
   ref FORMATETC pFormatEtc,
   IOleClientSite pClientSite,
   IStorage pStg,
   out object ppvObj
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olecreate)
