## WlanQueryInterface

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanQueryInterface(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   WLAN_INTF_OPCODE OpCode,
   IntPtr pReserved,
   out uint pdwDataSize,
   out IntPtr ppData,
   IntPtr pReserved2
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanqueryinterface)
