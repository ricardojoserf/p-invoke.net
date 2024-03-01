## SetDevicePower

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetDevicePower(
   string pvDevice,
   uint dwDeviceFlags,
   DEVICE_POWER_STATE DeviceState
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/nspapi/nf-nspapi-setdevicepower)
