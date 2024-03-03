## WlanHostedNetworkInitSettings

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanHostedNetworkInitSettings(
   IntPtr hClientHandle,
   IntPtr pReserved,
   IntPtr pdwReasonCode,
   IntPtr pReserved2
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanhostednetworkinitsettings)
