## CoGetPSClsid

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetPSClsid(
   ref Guid riid,
   out Guid pClsid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetpsclsid)
