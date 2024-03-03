## WTSVirtualChannelRead

```csharp
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSVirtualChannelRead(
   IntPtr hChannelHandle,
   long TimeOut,
   IntPtr Buffer,
   int Length,
   ref int pBytesRead
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsvirtualchannelread)
