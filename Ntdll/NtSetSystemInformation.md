## NtSetSystemInformation

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSetSystemInformation(
   SYSTEM_INFORMATION_CLASS SystemInformationClass,
   IntPtr SystemInformation,
   uint SystemInformationLength
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/sysinfo/ntsetsysteminformation)
