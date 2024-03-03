## WTSLogoffSession

```csharp
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSLogoffSession(
   IntPtr hServer,
   int SessionId,
   bool bWait
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtslogoffsession)
