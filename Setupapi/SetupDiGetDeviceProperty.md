## SetupDiGetDeviceProperty

```csharp
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiGetDeviceProperty(
   IntPtr DeviceInfoSet,
   ref DeviceInfoData DeviceInfoData,
   ref DevicePropertyKey PropertyKey,
   out int PropertyType,
   IntPtr PropertyBuffer,
   int PropertyBufferSize,
   out int RequiredSize,
   uint Flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdigetdevicepropertyw)
