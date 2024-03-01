## SetupDiSetClassInstallParam

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiSetClassInstallParam(
   IntPtr DeviceInfoSet,
   ref DeviceInfoData DeviceInfoData,
   ref ClassInstallHeader ClassInstallParams,
   uint ClassInstallParamsSize
);
```

Microsoft documentation: (TODO)
