## SetDevicePower

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetDevicePower(
   string pvDevice,
   uint dwDeviceFlags,
   DEVICE_POWER_STATE DeviceState
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/embedded/ms920584(v=msdn.10))
