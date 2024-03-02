## DeviceEventWorker

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DeviceEventWorker(
   IntPtr hwnd,
   uint eventCode,
   IntPtr dwEventData,
   IntPtr dwExtraInfo
);
```

