## PfBindInterfaceToIPAddress

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int PfBindInterfaceToIPAddress(
   IP_ADAPTER_BINDING_INFO AdapterInfo,
   IntPtr RequestHandle,
   IntPtr Overlapped
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-pfbindinterfacetoipaddress)
