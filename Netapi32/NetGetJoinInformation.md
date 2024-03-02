## NetGetJoinInformation

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetGetJoinInformation(
   string Server,
   out IntPtr Buffer,
   out JoinStatus Status
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmjoin/nf-lmjoin-netgetjoininformation)
