## WTSRegisterSessionNotification

```csharp
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSRegisterSessionNotification(
   IntPtr hWnd,
   int dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsregistersessionnotification)
