## Writeprocessmemory

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteProcessMemory(
   IntPtr hProcess,
   IntPtr lpBaseAddress,
   [MarshalAs(
   UnmanagedType.LPArray)] byte[] lpBuffer,
   uint nSize,
   out uint lpNumberOfBytesWritten
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-writeprocessmemory)
