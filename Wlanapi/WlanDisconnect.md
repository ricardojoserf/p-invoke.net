## WlanDisconnect

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanDisconnect(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlandisconnect)
