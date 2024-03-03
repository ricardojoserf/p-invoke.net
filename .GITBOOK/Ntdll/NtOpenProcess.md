## NtOpenProcess

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtOpenProcess(
   out IntPtr ProcessHandle,
   uint DesiredAccess,
   IntPtr ObjectAttributes,
   ref CLIENT_ID ClientId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/ntddk/nf-ntddk-ntopenprocess)
