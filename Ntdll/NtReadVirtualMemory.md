## NtReadVirtualMemory

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtReadVirtualMemory(
   IntPtr ProcessHandle,
   IntPtr BaseAddress,
   [Out] byte[] Buffer,
   uint NumberOfBytesToRead,
   out uint NumberOfBytesRead
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-readprocessmemory)
