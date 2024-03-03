## NtQueryInformationProcess

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryInformationProcess(
   IntPtr ProcessHandle,
   PROCESSINFOCLASS ProcessInformationClass,
   IntPtr ProcessInformation,
   uint ProcessInformationLength,
   out uint ReturnLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntqueryinformationprocess)
