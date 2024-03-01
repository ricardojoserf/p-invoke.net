## WlanHostedNetworkForceStop

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanHostedNetworkForceStop(
   IntPtr hClientHandle,
   IntPtr pReserved,
   IntPtr pdwReasonCode,
   IntPtr pReserved2
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanhostednetworkforcestop)
