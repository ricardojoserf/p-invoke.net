## NtProtectVirtualMemory

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtProtectVirtualMemory(
   IntPtr ProcessHandle,
   ref IntPtr BaseAddress,
   ref uint RegionSize,
   uint NewProtect,
   out uint OldProtect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-virtualprotectex)
