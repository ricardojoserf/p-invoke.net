## WTSEnumerateSessions

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSEnumerateSessions(
   IntPtr hServer,
   int Reserved,
   int Version,
   ref IntPtr ppSessionInfo,
   ref int pCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsenumeratesessionsa)
