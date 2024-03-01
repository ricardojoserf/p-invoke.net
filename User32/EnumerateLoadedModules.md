## EnumerateLoadedModules

```
[DllImport("psapi.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumerateLoadedModules(
   IntPtr hProcess,
   ref IntPtr lphModule,
   uint cb,
   out uint lpcbNeeded
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-enumerateloadedmodules)
