## PowerSettingRegisterNotification

```csharp
[DllImport("powrprof.dll", SetLastError = true)]
public static extern IntPtr PowerSettingRegisterNotification(
   IntPtr SettingGuid,
   uint Flags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/powersetting/nf-powersetting-powersettingregisternotification)
