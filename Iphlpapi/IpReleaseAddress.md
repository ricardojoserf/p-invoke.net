## IpReleaseAddress

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int IpReleaseAddress(
   ref IP_ADAPTER_INDEX_MAP AdapterInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-ipreleaseaddress)
