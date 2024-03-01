## NtQueryDirectoryObject

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryDirectoryObject(
   IntPtr DirectoryHandle,
   IntPtr Buffer,
   uint Length,
   bool ReturnSingleEntry,
   bool RestartScan,
   ref uint Context,
   out uint ReturnLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-zwquerydirectoryobject)
