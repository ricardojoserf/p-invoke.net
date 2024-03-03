## RegisterPowerSettingNotification

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr RegisterPowerSettingNotification(
   IntPtr hRecipient,
   ref Guid PowerSettingGuid,
   uint Flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-registerpowersettingnotification)
