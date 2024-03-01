## ReadProcessMemory

```
[DllImport("kernel32.dll", SetLastError = true)]
public static extern bool ReadProcessMemory(
   IntPtr hProcess,
   IntPtr lpBaseAddress,
   [Out] byte[] lpBuffer,
   uint nSize,
   out uint lpNumberOfBytesRead
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-readprocessmemory)
