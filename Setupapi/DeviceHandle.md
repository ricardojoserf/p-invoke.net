## DeviceHandle

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr DeviceHandle(
   IntPtr DeviceInfoSet,
   ref DeviceInterfaceData InterfaceData,
   IntPtr DeviceInstancePath,
   uint Flags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupdiopendeviceinterface)
