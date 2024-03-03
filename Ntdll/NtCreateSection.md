## NtCreateSection

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtCreateSection(
   out IntPtr SectionHandle,
   uint DesiredAccess,
   IntPtr ObjectAttributes,
   ref LARGE_INTEGER MaximumSize,
   uint SectionPageProtection,
   uint AllocationAttributes,
   IntPtr FileHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-zwcreatesection)
