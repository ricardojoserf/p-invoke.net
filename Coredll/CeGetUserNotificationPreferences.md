## CeGetUserNotificationPreferences

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeGetUserNotificationPreferences(
   IntPtr hNotification,
   uint cPrefs,
   [Out] CE_NOTIFICATION_TRIGGER[] pTrigger
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/previous-versions/bb416365(v%3Dmsdn.10))
