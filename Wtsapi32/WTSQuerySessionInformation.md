## WTSQuerySessionInformation

```csharp
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSQuerySessionInformation(
   IntPtr hServer,
   int SessionId,
   WTS_INFO_CLASS WTSInfoClass,
   ref IntPtr ppBuffer,
   ref int pBytesReturned
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsquerysessioninformationa)
