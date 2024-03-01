## GetModuleInformation

```
[DllImport("psapi.dll", SetLastError = true)]
public static extern bool GetModuleInformation(
   IntPtr hProcess,
   IntPtr hModule,
   ref MODULEINFO lpmodinfo,
   uint cb
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-getmoduleinformation)
