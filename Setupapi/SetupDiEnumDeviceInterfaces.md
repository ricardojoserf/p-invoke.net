## SetupDiEnumDeviceInterfaces

```csharp
[DllImport("setupapi.dll", SetLastError = true)]
public static extern bool SetupDiEnumDeviceInterfaces(
   IntPtr DeviceInfoSet,
   IntPtr DeviceInfoData,
   ref Guid InterfaceClassGuid,
   uint MemberIndex,
   ref DeviceInterfaceData DeviceInterfaceData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdienumdeviceinterfaces)
