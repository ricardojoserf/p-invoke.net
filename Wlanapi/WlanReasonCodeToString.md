## WlanReasonCodeToString

```
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanReasonCodeToString(
   uint dwReasonCode,
   uint dwBufferSize,
   IntPtr pStringBuffer,
   IntPtr pReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanreasoncodetostring)
