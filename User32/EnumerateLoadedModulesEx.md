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

Microsoft documentation: (TODO)
