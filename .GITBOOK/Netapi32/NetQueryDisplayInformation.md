## NetQueryDisplayInformation

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetQueryDisplayInformation(
   string ServerName,
   uint Level,
   uint Index,
   uint EntriesRequested,
   uint PreferredMaximumLength,
   out uint ReturnedEntryCount,
   out IntPtr SortedBuffer
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netquerydisplayinformation)
