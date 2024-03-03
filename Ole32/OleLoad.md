## OleLoad

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleLoad(
   IStorage pStg,
   ref Guid riid,
   IOleClientSite pClientSite,
   out object ppvObj
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-oleload)
