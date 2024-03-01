## WlanSetProfilePosition

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanSetProfilePosition(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   [MarshalAs(UnmanagedType.LPWStr)] string strProfileName,
   uint dwPosition,
   IntPtr pReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlansetprofileposition)
