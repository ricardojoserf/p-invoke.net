## NetServerGetInfo

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetServerGetInfo(
   string ServerName,
   uint Level,
   out IntPtr Buffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmserver/nf-lmserver-netservergetinfo)
