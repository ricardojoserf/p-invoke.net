## CeGetUserNotification

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeGetUserNotification(
   IntPtr hNotifications,
   uint cNotification,
   [Out] CE_NOTIFICATION[] lpNotifications
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/previous-versions/bb416362(v%3Dmsdn.10))
