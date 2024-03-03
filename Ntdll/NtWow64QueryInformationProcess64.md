## NtWow64QueryInformationProcess64

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtWow64QueryInformationProcess64(
   IntPtr ProcessHandle,
   uint ProcessInformationClass,
   ref IntPtr ProcessInformation,
   uint ProcessInformationLength,
   out uint ReturnLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wow64apiset/nf-wow64apiset-iswow64process2)
