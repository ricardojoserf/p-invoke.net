## NtClose

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtClose(
   IntPtr hObject
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-zwclose)
