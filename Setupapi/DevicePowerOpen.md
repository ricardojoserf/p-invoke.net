## DevicePowerOpen

```csharp
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr DevicePowerOpen(
   IntPtr DeviceInfoSet,
   ref DeviceInterfaceData InterfaceData,
   IntPtr DeviceInstancePath,
   uint Flags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-devicepoweropen)
