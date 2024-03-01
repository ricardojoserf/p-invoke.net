## DevicePowerOpen

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr DevicePowerOpen(
   IntPtr DeviceInfoSet,
   ref DeviceInterfaceData InterfaceData,
   IntPtr DeviceInstancePath,
   uint Flags
);
```

Microsoft documentation: (TODO)
