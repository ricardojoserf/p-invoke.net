## NetMessageBufferSend

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetMessageBufferSend(
   string servername,
   string msgname,
   string fromname,
   IntPtr Buffer,
   uint buflen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmmsg/nf-lmmsg-netmessagebuffersend)
