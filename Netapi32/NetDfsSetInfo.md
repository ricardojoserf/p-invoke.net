## NetDfsSetInfo

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetDfsSetInfo(
   string DfsEntryPath,
   string ServerName,
   string ShareName,
   uint Level,
   IntPtr Buffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmdfs/nf-lmdfs-netdfssetinfo)
