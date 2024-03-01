## PrivacyGetZonePreference

```
[DllImport("wininet.dll", SetLastError = true)]
public static extern bool PrivacyGetZonePreference(
   uint dwZone,
   uint dwType,
   IntPtr pBuffer,
   ref uint dwBufferLength,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-privacygetzonepreference)
