## NetUseEnum

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetUseEnum(
   string UncServerName,
   uint Level,
   out IntPtr Buffer,
   uint PrefMaxLen,
   out uint EntriesRead,
   out uint TotalEntries,
   ref uint ResumeHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmuse/nf-lmuse-netuseenum)
