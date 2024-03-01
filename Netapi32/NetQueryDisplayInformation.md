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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmapibuf/nf-lmapibuf-netquerydisplayinformation)
