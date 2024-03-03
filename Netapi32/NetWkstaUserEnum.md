## NetWkstaUserEnum

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetWkstaUserEnum(
   string ServerName,
   uint Level,
   out IntPtr Buffer,
   uint PrefMaxLen,
   out uint EntriesRead,
   out uint TotalEntries,
   ref uint ResumeHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmwksta/nf-lmwksta-netwkstauserenum)
