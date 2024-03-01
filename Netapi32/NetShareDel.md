## NetShareDel

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetShareDel(
   string servername,
   string netname,
   uint reserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmshare/nf-lmshare-netsharedel)
