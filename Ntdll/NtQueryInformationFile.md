## NtQueryInformationFile

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryInformationFile(
   IntPtr FileHandle,
   ref IO_STATUS_BLOCK IoStatusBlock,
   IntPtr FileInformation,
   uint Length,
   FILE_INFORMATION_CLASS FileInformationClass
);
```

Microsoft documentation: (TODO)
