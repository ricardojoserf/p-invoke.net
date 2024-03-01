## PfCreateInterface

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int PfCreateInterface(
   ref IP_ADAPTER_BINDING_INFO AdapterInfo,
   ref uint NdisStatus
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-pfcreateinterface)
