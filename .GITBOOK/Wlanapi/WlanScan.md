## WlanScan

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanScan(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   IntPtr pDot11Ssid,
   IntPtr pIeData,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanscan)
