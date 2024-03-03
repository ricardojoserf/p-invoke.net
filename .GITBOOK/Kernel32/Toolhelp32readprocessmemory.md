## Toolhelp32readprocessmemory

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool Toolhelp32ReadProcessMemory(uint th32ProcessID,
   IntPtr lpBaseAddress,
   IntPtr lpBuffer,
   uint cbRead,
   IntPtr lpNumberOfBytesRead
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-toolhelp32readprocessmemory)
