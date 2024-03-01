## WlanEnumInterfaces

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanEnumInterfaces(
   IntPtr hClientHandle,
   IntPtr pReserved,
   out IntPtr ppInterfaceList
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanenuminterfaces)
