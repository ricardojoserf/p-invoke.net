## netserverenum

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetServerEnum(string ServerName,
   uint Level,
   out IntPtr Buffer,
   uint PrefMaxLen,
   out uint EntriesRead,
   out uint TotalEntries,
   uint ServerType,
   string Domain,
   string ResumeHandle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmserver/nf-lmserver-netserverenum)
