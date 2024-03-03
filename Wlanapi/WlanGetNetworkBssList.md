## WlanGetNetworkBssList

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanGetNetworkBssList(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   ref GUID pDot11Ssid,
   DOT11_BSS_TYPE dot11BssType,
   bool bSecurityEnabled,
   IntPtr pReserved,
   out IntPtr ppWlanBssList
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlangetnetworkbsslist)
