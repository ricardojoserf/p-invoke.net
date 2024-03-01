## GetNetworkParams

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetNetworkParams(
   IntPtr pFixedInfo,
   ref uint pOutBufLen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getnetworkparams)
