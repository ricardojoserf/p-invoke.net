## RtlGetVersion

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int RtlGetVersion(
   ref OSVERSIONINFOEXW lpVersionInformation
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-rtlgetversion)
