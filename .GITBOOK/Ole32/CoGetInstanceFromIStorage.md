## CoGetInstanceFromIStorage

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetInstanceFromIStorage(
   COSERVERINFO pServerInfo,
   ref FILETIME pft,
   ref Guid riid,
   IUnknown punkOuter,
   uint dwClsCtx,
   IntPtr pvReserved,
   uint ciidExclude,
   Guid[] rgiidExclude,
   out IntPtr ppv
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-cogetinstancefromistorage)
