## OleCreateLinkToFile

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreateLinkToFile(
   [MarshalAs(UnmanagedType.LPWStr)] string lpszFileName,
   ref Guid riid,
   uint renderopt,
   ref FORMATETC pFormatEtc,
   IOleClientSite pClientSite,
   IStorage pStg,
   out object ppvObj
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olecreatelinktofile)
