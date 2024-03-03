## NtQuerySystemTime

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern void NtQuerySystemTime(
   out LARGE_INTEGER SystemTime
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-kequerysystemtime)
