## NtQuerySymbolicLinkObject

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQuerySymbolicLinkObject(
   IntPtr LinkHandle,
   ref UNICODE_STRING LinkTarget,
   ref uint ReturnedLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-zwquerysymboliclinkobject)
