## CeGetUserNotification

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeGetUserNotification(
   IntPtr hNotifications,
   uint cNotification,
   [Out] CE_NOTIFICATION[] lpNotifications
);
```

Microsoft documentation: (TODO)
