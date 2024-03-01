## NtSetSystemInformation

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSetSystemInformation(
   SYSTEM_INFORMATION_CLASS SystemInformationClass,
   IntPtr SystemInformation,
   uint SystemInformationLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-zwsetsysteminformation)
