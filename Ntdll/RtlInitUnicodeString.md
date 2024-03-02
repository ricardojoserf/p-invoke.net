## RtlInitUnicodeString

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern void RtlInitUnicodeString(
   out UNICODE_STRING DestinationString,
   [MarshalAs(UnmanagedType.LPWStr)] string SourceString
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-rtlinitunicodestring)
