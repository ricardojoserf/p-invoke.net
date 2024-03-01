## CoRegisterPSClsid

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoRegisterPSClsid(
   ref Guid riid,
   ref Guid rclsid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coregisterpsclsid)
