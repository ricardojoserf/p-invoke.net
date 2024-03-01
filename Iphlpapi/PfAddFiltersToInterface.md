## PfAddFiltersToInterface

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int PfAddFiltersToInterface(
   ref IP_ADAPTER_BINDING_INFO AdapterInfo,
   ref IP_PF_ADD_FILTER[] DemandFilter
);
```

Microsoft documentation: (TODO)
