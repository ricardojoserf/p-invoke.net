## NtRaiseHandError

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern void NtRaiseHandError(
   uint BugCheckCode,
   uint BugCheckParameter1,
   uint BugCheckParameter2,
   uint BugCheckParameter3,
   uint BugCheckParameter4
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-kebugcheckex)
