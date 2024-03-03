## CoGetMarshalSizeMax

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetMarshalSizeMax(
   out uint pulSize,
   ref Guid riid,
   IUnknown pUnk,
   uint dwDestContext,
   IntPtr pvDestContext,
   uint mshlflags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetmarshalsizemax)
