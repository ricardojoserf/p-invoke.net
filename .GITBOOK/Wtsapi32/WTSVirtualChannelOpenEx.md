## WTSVirtualChannelOpenEx

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern IntPtr WTSVirtualChannelOpenEx(
   int SessionId,
   string pVirtualName,
   int OpenFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsvirtualchannelopenex)
