## CoCreateInstanceEx

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoCreateInstanceEx(
   ref Guid rclsid,
   IUnknown pUnkOuter,
   uint dwClsCtx,
   COSERVERINFO pServerInfo,
   uint cmq,
   MULTI_QI[] pResults
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cocreateinstanceex)
