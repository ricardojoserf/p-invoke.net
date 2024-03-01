## SetupDiEnumDeviceInfo

```
[DllImport("setupapi.dll", SetLastError = true)]
public static extern bool SetupDiEnumDeviceInfo(
   IntPtr DeviceInfoSet,
   uint MemberIndex,
   ref DeviceInfoData DeviceInfoData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdienumdeviceinfow)
