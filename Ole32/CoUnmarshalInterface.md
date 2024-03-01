## CoUnmarshalInterface

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoUnmarshalInterface(
   IStream pStm,
   ref Guid riid,
   out IntPtr ppv
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-counmarshalinterface)
