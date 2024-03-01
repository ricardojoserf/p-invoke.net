## SetupDiEnumDeviceInfo

```
[DllImport("setupapi.dll", SetLastError = true)]
public static extern bool SetupDiEnumDeviceInfo(
   IntPtr DeviceInfoSet,
   uint MemberIndex,
   ref DeviceInfoData DeviceInfoData
);
```

Microsoft documentation: (TODO)
