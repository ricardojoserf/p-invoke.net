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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntqueryinformationfile)
