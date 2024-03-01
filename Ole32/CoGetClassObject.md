## CoGetClassObject

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetClassObject(
   ref Guid rclsid,
   uint dwClsContext,
   COSERVERINFO pServerInfo,
   ref Guid riid,
   out IntPtr ppv
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetclassobject)
