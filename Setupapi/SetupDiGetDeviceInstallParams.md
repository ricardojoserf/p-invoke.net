## SetupDiGetDeviceInstallParams

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiGetDeviceInstallParams(
   IntPtr DeviceInfoSet,
   ref DeviceInfoData DeviceInfoData,
   ref DeviceInstallParams DeviceInstallParams
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdigetdeviceinstallparamsw)
