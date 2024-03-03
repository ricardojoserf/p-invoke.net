## NetDfsAdd

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetDfsAdd(
   string DfsEntryPath,
   string ServerName,
   string ShareName,
   uint Flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmdfs/nf-lmdfs-netdfsadd)
