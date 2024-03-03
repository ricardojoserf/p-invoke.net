## NtQuerySystemInformation

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQuerySystemInformation(
   SYSTEM_INFORMATION_CLASS SystemInformationClass,
   IntPtr SystemInformation,
   uint SystemInformationLength,
   out uint ReturnLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntquerysysteminformation)
