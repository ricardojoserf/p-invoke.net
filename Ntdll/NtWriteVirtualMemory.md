## NtWriteVirtualMemory

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtWriteVirtualMemory(
   IntPtr ProcessHandle,
   IntPtr BaseAddress,
   [In] byte[] Buffer,
   uint NumberOfBytesToWrite,
   out uint NumberOfBytesWritten
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-writeprocessmemory)
