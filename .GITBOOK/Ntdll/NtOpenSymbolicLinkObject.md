## NtOpenSymbolicLinkObject

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtOpenSymbolicLinkObject(
   out IntPtr LinkHandle,
   uint DesiredAccess,
   IntPtr ObjectAttributes
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-zwopensymboliclinkobject)
