## PrivacyGetZonePreference

```csharp
[DllImport("wininet.dll", SetLastError = true)]
public static extern bool PrivacyGetZonePreference(
   uint dwZone,
   uint dwType,
   IntPtr pBuffer,
   ref uint dwBufferLength,
   uint dwFlags
);
```

