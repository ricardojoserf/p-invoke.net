## CoGetInterfaceAndReleaseStream

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetInterfaceAndReleaseStream(
   IStream pStm,
   ref Guid riid,
   out IntPtr ppv
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetinterfaceandreleasestream)
