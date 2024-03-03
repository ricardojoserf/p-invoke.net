## CreateDataCache

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateDataCache(
   IUnknown pUnknown,
   ref Guid rclsid,
   ref Guid riid,
   out IUnknown ppv
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-createdatacache)
