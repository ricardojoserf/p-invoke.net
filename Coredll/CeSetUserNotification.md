## CeSetUserNotification

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeSetUserNotification(
   CE_NOTIFICATION_TRIGGER* pTrigger,
   IntPtr hNotification,
   uint hNotification2
);
```

