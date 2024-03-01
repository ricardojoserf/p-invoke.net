## NetSessionEnum

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetSessionEnum(
   string ServerName,
   string UncClientName,
   string UserName,
   uint Level,
   out IntPtr Buffer,
   uint PrefMaxLen,
   out uint EntriesRead,
   out uint TotalEntries,
   ref uint ResumeHandle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmshare/nf-lmshare-netsessionenum)
