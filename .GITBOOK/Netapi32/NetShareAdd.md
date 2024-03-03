## NetShareAdd

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetShareAdd(
   string servername,
   uint level,
   ref SHARE_INFO_2 Buf,
   out uint ParmError
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmshare/nf-lmshare-netshareadd)
