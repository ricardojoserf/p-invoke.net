## OleCreateEmbeddingHelper

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreateEmbeddingHelper(
   ref Guid rclsid,
   IUnknown pUnkOuter,
   uint dwClsCtx,
   IntPtr pCF,
   out IOleEmbeddingHelper ppOEH
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olecreateembeddinghelper)
