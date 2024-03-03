## GetModuleInformation

```csharp
[DllImport("psapi.dll", SetLastError = true)]
public static extern bool GetModuleInformation(
   IntPtr hProcess,
   IntPtr hModule,
   ref MODULEINFO lpmodinfo,
   uint cb
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-getmoduleinformation)
