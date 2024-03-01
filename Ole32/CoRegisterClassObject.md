## CoRegisterClassObject

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoRegisterClassObject(
   ref Guid rclsid,
   IUnknown pUnk,
   uint dwClsContext,
   uint flags,
   out uint lpdwRegister
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coregisterclassobject)
