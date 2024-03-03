## SetupDiCallClassInstaller

```csharp
[DllImport("setupapi.dll", SetLastError = true)]
public static extern bool SetupDiCallClassInstaller(
   uint InstallFunction,
   IntPtr DeviceInfoSet,
   ref DeviceInterfaceData InterfaceData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdicallclassinstaller)
