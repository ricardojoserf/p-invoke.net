## WlanSetInterface

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanSetInterface(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   WLAN_INTF_OPCODE OpCode,
   uint dwDataSize,
   IntPtr pvData,
   IntPtr pReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlansetinterface)
