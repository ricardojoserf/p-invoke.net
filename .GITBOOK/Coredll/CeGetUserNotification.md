## CeGetUserNotification

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeGetUserNotification(
   IntPtr hNotifications,
   uint cNotification,
   [Out] CE_NOTIFICATION[] lpNotifications
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/embedded/ms908076(v%3Dmsdn.10))
