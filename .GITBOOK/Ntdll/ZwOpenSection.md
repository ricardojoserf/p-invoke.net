## ZwOpenSection

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int ZwOpenSection(
   out IntPtr SectionHandle,
   uint DesiredAccess,
   IntPtr ObjectAttributes
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-zwopensection)
