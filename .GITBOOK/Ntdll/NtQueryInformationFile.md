## NtQueryInformationFile

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryInformationFile(
   IntPtr FileHandle,
   ref IO_STATUS_BLOCK IoStatusBlock,
   IntPtr FileInformation,
   uint Length,
   FILE_INFORMATION_CLASS FileInformationClass
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows-hardware/drivers/ddi/ntifs/nf-ntifs-ntqueryinformationfile)
