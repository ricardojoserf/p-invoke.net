## WlanRegisterNotification

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanRegisterNotification(
   IntPtr hClientHandle,
   WLAN_NOTIFICATION_SOURCE dwNotifSource,
   bool bIgnoreDuplicate,
   WLAN_NOTIFICATION_CALLBACK funcCallback,
   IntPtr pCallbackContext,
   IntPtr pReserved,
   out WLAN_NOTIFICATION_SOURCE pdwPrevNotifSource
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanregisternotification)
