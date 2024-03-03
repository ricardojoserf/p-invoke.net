## WlanGetProfile

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanGetProfile(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   [MarshalAs(UnmanagedType.LPWStr)] string strProfileName,
   IntPtr pReserved,
   [MarshalAs(UnmanagedType.LPWStr)] out string pstrProfileXml,
   ref WLAN_PROFILE_GET_FLAGS pdwFlags,
   IntPtr pReserved2
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlangetprofile)
