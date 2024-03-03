## GetDeviceUniqueID

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool GetDeviceUniqueID(
   [Out] byte[] AppID,
   uint cbSize,
   DeviceUniqueID dwDeviceIDVersion,
   IntPtr lpData,
   IntPtr dwSize
);
```

