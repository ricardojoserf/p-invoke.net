## GetRawInputDeviceInfo

```
[DllImport("user32.dll", SetLastError = true)]
public static extern uint GetRawInputDeviceInfo(
   IntPtr hDevice,
   uint uiCommand,
   IntPtr pData,
   ref uint pcbSize
);
```

[Microsoft documentation](TODO)
