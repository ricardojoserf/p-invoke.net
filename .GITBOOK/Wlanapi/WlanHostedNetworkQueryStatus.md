## WlanHostedNetworkQueryStatus

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanHostedNetworkQueryStatus(
   IntPtr hClientHandle,
   IntPtr ppWlanHostedNetworkStatus,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanhostednetworkquerystatus)
