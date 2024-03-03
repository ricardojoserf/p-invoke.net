## OleCreateLink

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreateLink(
   IOleClientSite pClientSite,
   [MarshalAs(UnmanagedType.LPStruct)] Guid rclsid,
   uint renderopt,
   ref FORMATETC pFormatEtc,
   IOleClientSite pClientSite2,
   IStorage pStg,
   out object ppvObj
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olecreatelink)
