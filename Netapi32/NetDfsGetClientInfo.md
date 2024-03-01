## NetDfsGetClientInfo

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetDfsGetClientInfo(
   string DfsEntryPath,
   string ServerName,
   string ShareName,
   uint Level,
   out IntPtr Buffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmdfs/nf-lmdfs-netdfsgetclientinfo)
