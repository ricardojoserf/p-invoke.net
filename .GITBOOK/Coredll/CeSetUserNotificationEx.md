## CeSetUserNotificationEx

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeSetUserNotificationEx(
   IntPtr hNotification,
   uint hNotification2,
   CE_NOTIFICATION_TRIGGER* pTrigger
);
```

