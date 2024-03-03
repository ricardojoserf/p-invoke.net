## SetupDiOpenDevRegKey

```csharp
[DllImport("setupapi.dll", SetLastError = true)]
public static extern IntPtr SetupDiOpenDevRegKey(
   IntPtr DeviceInfoSet,
   ref DeviceInfoData DeviceInfoData,
   uint Scope,
   uint HwProfile,
   uint KeyType,
   uint samDesired
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdiopendevregkey)
