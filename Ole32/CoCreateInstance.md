## CoCreateInstance

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoCreateInstance(
   ref Guid rclsid,
   IntPtr pUnkOuter,
   uint dwClsContext,
   ref Guid riid,
   out IntPtr ppv
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cocreateinstance)
