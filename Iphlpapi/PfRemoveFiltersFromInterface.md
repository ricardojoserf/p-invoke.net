## PfRemoveFiltersFromInterface

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int PfRemoveFiltersFromInterface(
   ref IP_ADAPTER_BINDING_INFO AdapterInfo,
   ref IP_PF_REMOVE_FILTER[] DemandFilter
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-pfremovefiltersfrominterface)
