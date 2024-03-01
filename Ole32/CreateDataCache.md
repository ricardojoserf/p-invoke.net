## CreateDataCache

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateDataCache(
   IUnknown pUnknown,
   ref Guid rclsid,
   ref Guid riid,
   out IUnknown ppv
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/objidl/nf-objidl-createdatacache)
