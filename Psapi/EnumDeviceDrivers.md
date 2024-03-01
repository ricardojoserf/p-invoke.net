## EnumDeviceDrivers

```
[DllImport("psapi.dll", SetLastError = true)]
public static extern bool EnumDeviceDrivers(
   [MarshalAs(UnmanagedType.LPArray,
   ArraySubType = UnmanagedType.U4)] [In,
   Out] uint[] lpImageBase,
   uint cb,
   out uint lpcbNeeded
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-enumdevicedrivers)
