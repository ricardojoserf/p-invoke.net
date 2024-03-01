## NtSetProcessIsCritical

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSetInformationProcess(
   IntPtr ProcessHandle,
   PROCESS_INFORMATION_CLASS ProcessInformationClass,
   IntPtr ProcessInformation,
   uint ProcessInformationLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-ntsetinformationprocess)
