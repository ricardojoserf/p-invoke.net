## PfAddFiltersToInterface

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int PfAddFiltersToInterface(
   ref IP_ADAPTER_BINDING_INFO AdapterInfo,
   ref IP_PF_ADD_FILTER[] DemandFilter
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/aa376640(v=vs.85))
