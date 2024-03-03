## WlanSetProfileList

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanSetProfileList(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   uint dwItems,
   IntPtr pProfileList,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlansetprofilelist)
