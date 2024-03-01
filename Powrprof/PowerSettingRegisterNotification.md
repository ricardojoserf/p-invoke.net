## PowerSettingRegisterNotification

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern IntPtr PowerSettingRegisterNotification(
   IntPtr SettingGuid,
   uint Flags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-powersettingregisternotification)
