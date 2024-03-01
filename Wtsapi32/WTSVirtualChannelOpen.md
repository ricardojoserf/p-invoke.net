## WTSVirtualChannelOpen

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern IntPtr WTSVirtualChannelOpen(
   IntPtr hServer,
   int SessionId,
   string pVirtualName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsvirtualchannelopen)
