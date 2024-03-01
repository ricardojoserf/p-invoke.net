## WlanGetAvailableNetworkList

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanGetAvailableNetworkList(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   uint dwFlags,
   IntPtr pReserved,
   out IntPtr ppAvailableNetworkList
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlangetavailablenetworklist)
