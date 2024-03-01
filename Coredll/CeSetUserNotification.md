## CeSetUserNotification

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeSetUserNotification(
   CE_NOTIFICATION_TRIGGER* pTrigger,
   IntPtr hNotification,
   uint hNotification2
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/previous-versions/bb416397(v%3Dmsdn.10))
