## NetUserAdd

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetUserAdd(
   string ServerName,
   uint Level,
   ref USER_INFO_2 Buf,
   out uint ParmError
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netuseradd)
