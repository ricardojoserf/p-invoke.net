## EnumerateLoadedModulesEx

```csharp
[DllImport("psapi.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumerateLoadedModulesEx(
   IntPtr hProcess,
   ref IntPtr lphModule,
   uint cb,
   out uint lpcbNeeded,
   uint dwFilterFlag
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dbghelp/nf-dbghelp-enumerateloadedmodulesexw)
