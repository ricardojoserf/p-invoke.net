## SetupDiGetDeviceInterfaceDetail

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiGetDeviceInterfaceDetail(
   IntPtr DeviceInfoSet,
   ref DeviceInterfaceData DeviceInterfaceData,
   IntPtr DeviceInterfaceDetailData,
   uint DeviceInterfaceDetailDataSize,
   ref uint RequiredSize,
   IntPtr DeviceInfoData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdigetdeviceinterfacedetailw)
