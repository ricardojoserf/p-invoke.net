## OleCreateLinkFromDataEx

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreateLinkFromDataEx(
   IDataObject pSrcDataObj,
   ref Guid riid,
   uint renderopt,
   ref FORMATETC pFormatEtc,
   IOleClientSite pClientSite,
   IStorage pStg,
   out object ppvObj,
   uint dwFlags,
   uint dwAdvf,
   uint dwReserved,
   uint[] pdwConnection,
   IAdviseSink[] pAdvSink
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olecreatelinkfromdataex)
