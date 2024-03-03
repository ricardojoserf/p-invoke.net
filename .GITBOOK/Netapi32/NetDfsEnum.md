## NetDfsEnum

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetDfsEnum(
   string DfsName,
   uint Level,
   uint PrefMaxLen,
   out IntPtr Buffer,
   out uint EntriesRead,
   out uint ResumeHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmdfs/nf-lmdfs-netdfsenum)
