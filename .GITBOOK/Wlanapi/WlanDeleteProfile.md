## WlanDeleteProfile

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint WlanDeleteProfile(
   IntPtr hClientHandle,
   ref GUID pInterfaceGuid,
   [MarshalAs(UnmanagedType.LPWStr)] string strProfileName,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wlanapi/nf-wlanapi-wlandeleteprofile)
