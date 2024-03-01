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

[Microsoft documentation](https://docs.microsoft.com/en-us/previous-versions/bb431752(v%3Dmsdn.10))
