## SetupDiSetClassInstallParams

```csharp
[DllImport("setupapi.dll", SetLastError = true)]
public static extern bool SetupDiSetClassInstallParams(
   IntPtr DeviceInfoSet,
   ref DeviceInfoData DeviceInfoData,
   ref ClassInstallHeader ClassInstallParams,
   uint ClassInstallParamsSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdisetclassinstallparamsw)
