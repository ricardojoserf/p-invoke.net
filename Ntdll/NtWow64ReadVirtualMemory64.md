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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wow64apiset/nf-wow64apiset-wow64readvirtualmemorycharts-32)
