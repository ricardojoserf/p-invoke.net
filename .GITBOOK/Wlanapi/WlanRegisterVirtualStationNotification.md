## WlanRegisterVirtualStationNotification

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanRegisterVirtualStationNotification(
   IntPtr hClientHandle,
   bool bRegister,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanregistervirtualstationnotification)
