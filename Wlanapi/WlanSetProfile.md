## WlanSetProfile

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanSetProfile(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   WLAN_PROFILE_FLAGS dwFlags,
   [MarshalAs(
   UnmanagedType.LPWStr)] string strProfileXml,
   [MarshalAs(
   UnmanagedType.LPWStr)] string strAllUserProfileSecurity,
   bool bOverwrite,
   IntPtr pReserved,
   out WLAN_REASON_CODE pdwReasonCode
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlansetprofile)
