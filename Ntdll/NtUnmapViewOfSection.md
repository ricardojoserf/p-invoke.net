## NtUnmapViewOfSection

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtUnmapViewOfSection(
   IntPtr ProcessHandle,
   IntPtr BaseAddress
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-unmapviewofsection)
