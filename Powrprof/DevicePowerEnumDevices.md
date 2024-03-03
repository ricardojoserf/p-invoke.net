## DevicePowerEnumDevices

```csharp
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool DevicePowerEnumDevices(
   uint QueryIndex,
   uint QueryInterpretationFlags,
   ref Guid SubGroupOfPowerSetting,
   uint Flags,
   ref IntPtr DeviceInformationSet
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-devicepowerenumdevices)
