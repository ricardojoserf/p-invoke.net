## PrivacySetZonePreference

```
[DllImport("wininet.dll", SetLastError = true)]
public static extern bool PrivacySetZonePreference(
   uint dwZone,
   uint dwType,
   IntPtr pBuffer,
   uint dwBufferLength,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-privacysetzonepreferencew)
