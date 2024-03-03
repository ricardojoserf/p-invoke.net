## WlanHostedNetworkQuerySecondaryKey

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanHostedNetworkQuerySecondaryKey(
   IntPtr hClientHandle,
   IntPtr pdwKeyLength,
   IntPtr ppucKeyData,
   IntPtr pbIsPassPhrase,
   IntPtr pbPersistent,
   IntPtr pdwReasonCode,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlanhostednetworkquerysecondarykey)
