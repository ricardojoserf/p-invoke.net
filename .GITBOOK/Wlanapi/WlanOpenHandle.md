## WlanOpenHandle

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanOpenHandle(
   uint dwClientVersion,
   IntPtr pReserved,
   out uint pdwNegotiatedVersion,
   out IntPtr phClientHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanopenhandle)
