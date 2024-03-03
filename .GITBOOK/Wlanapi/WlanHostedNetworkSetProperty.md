## WlanHostedNetworkSetProperty

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanHostedNetworkSetProperty(
   IntPtr hClientHandle,
   WLAN_HOSTED_NETWORK_OPCODE OpCode,
   uint dwDataSize,
   IntPtr pvData,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanhostednetworksetproperty)
