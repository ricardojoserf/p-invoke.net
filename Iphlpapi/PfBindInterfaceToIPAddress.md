## PfBindInterfaceToIPAddress

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int PfBindInterfaceToIPAddress(
   IP_ADAPTER_BINDING_INFO AdapterInfo,
   IntPtr RequestHandle,
   IntPtr Overlapped
);
```

Microsoft documentation: (TODO)
