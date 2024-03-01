## WlanGetProfileList

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanGetProfileList(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   IntPtr pReserved,
   out IntPtr ppProfileList
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlangetprofilelist)
