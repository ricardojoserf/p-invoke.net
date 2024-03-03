## SetupDiSetClassInstallParam

```csharp
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupDiSetClassInstallParam(
   IntPtr DeviceInfoSet,
   ref DeviceInfoData DeviceInfoData,
   ref ClassInstallHeader ClassInstallParams,
   uint ClassInstallParamsSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdisetclassinstallparamsa)
