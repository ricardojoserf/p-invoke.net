## NtWow64ReadVirtualMemory64

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtWow64ReadVirtualMemory64(
   IntPtr ProcessHandle,
   ulong BaseAddress,
   [Out] byte[] Buffer,
   ulong Size,
   out ulong NumberOfBytesRead
);
```

