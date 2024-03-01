## SetupDiGetDeviceInstanceId

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiGetDeviceInstanceId(
   IntPtr DeviceInfoSet,
   ref DeviceInfoData DeviceInfoData,
   StringBuilder DeviceInstanceId,
   int DeviceInstanceIdSize,
   ref int RequiredSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdigetdeviceinstanceidw)
