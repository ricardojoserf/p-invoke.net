## EnumerateLoadedModulesEx

```
[DllImport("psapi.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumerateLoadedModulesEx(
   IntPtr hProcess,
   ref IntPtr lphModule,
   uint cb,
   out uint lpcbNeeded,
   uint dwFilterFlag
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-enumerateloadedmodulesex)
