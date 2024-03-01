## WTSVirtualChannelWrite

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSVirtualChannelWrite(
   IntPtr hChannelHandle,
   IntPtr Buffer,
   int Length,
   ref int pBytesWritten
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsvirtualchannelwrite)
