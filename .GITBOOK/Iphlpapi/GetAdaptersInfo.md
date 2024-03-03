## GetAdaptersInfo

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetAdaptersInfo(
   IntPtr pAdapterInfo,
   ref uint pOutBufLen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getadaptersinfo)
