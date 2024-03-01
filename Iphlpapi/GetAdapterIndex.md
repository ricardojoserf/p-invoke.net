## GetAdapterIndex

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetAdapterIndex(
   string AdapterName,
   out uint IfIndex
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getadapterindex)
