## NetUserGetGroups

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetUserGetGroups(
   string ServerName,
   string UserName,
   uint Level,
   out IntPtr Buffer,
   uint PrefMaxLen,
   out uint EntriesRead,
   out uint TotalEntries
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netusergetgroups)
