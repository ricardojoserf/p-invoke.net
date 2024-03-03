## NetLocalGroupGetMembers

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetLocalGroupGetMembers(
   string ServerName,
   string LocalGroupName,
   uint Level,
   out IntPtr Buffer,
   uint PrefMaxLen,
   out uint EntriesRead,
   out uint TotalEntries,
   ref uint ResumeHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netlocalgroupgetmembers)
