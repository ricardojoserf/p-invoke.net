## NetlGroupEnum

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetGroupEnum(
   string ServerName,
   uint Level,
   out IntPtr Buffer,
   uint PrefMaxLen,
   out uint EntriesRead,
   out uint TotalEntries,
   ref uint ResumeHandle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netgroupenum)
