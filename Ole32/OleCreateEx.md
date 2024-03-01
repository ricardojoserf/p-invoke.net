## OleCreateEx

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreateEx(
   ref Guid rclsid,
   ref Guid riid,
   uint renderopt,
   ref FORMATETC pFormatEtc,
   uint cAdvise,
   uint[] advf,
   IAdviseSink[] pAdvSink,
   uint[] pdwConnection,
   IStorage pStg,
   out object ppvObj
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olecreateex)
