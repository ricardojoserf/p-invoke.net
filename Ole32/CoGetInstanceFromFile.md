## CoGetInstanceFromFile

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetInstanceFromFile(
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

[Microsoft documentation](TODO)
