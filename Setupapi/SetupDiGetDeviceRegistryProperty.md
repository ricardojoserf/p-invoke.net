## SetupDiGetDeviceRegistryProperty

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiGetDeviceRegistryProperty(
   IntPtr DeviceInfoSet,
   ref DeviceInfoData DeviceInfoData,
   int Property,
   out int PropertyRegDataType,
   IntPtr PropertyBuffer,
   int PropertyBufferSize,
   out int RequiredSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdigetdeviceregistrypropertyw)
