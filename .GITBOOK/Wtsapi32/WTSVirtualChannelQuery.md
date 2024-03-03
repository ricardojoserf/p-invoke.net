## WTSVirtualChannelQuery

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSVirtualChannelQuery(
   IntPtr hChannelHandle,
   WTS_VIRTUAL_CLASS WtsVirtualClass,
   ref IntPtr ppBuffer,
   ref int pBytesReturned
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsvirtualchannelquery)
