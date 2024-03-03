## NtQueryDirectoryObject

```csharp
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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/devnotes/ntquerydirectoryobject)
