## WlanConnect

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanConnect(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   ref WLAN_CONNECTION_PARAMETERS pConnectionParameters,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanconnect)
