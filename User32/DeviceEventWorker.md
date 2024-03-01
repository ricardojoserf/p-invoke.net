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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-deviceeventworker)
