## NetDfsGetInfo

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetDfsGetInfo(
   string DfsEntryPath,
   string ServerName,
   string ShareName,
   uint Level,
   out IntPtr Buffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmdfs/nf-lmdfs-netdfsgetinfo)
