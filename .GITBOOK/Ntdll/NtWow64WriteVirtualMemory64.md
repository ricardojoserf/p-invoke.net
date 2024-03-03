## NtWow64WriteVirtualMemory64

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtWow64WriteVirtualMemory64(
   IntPtr ProcessHandle,
   ulong BaseAddress,
   [In] byte[] Buffer,
   ulong Size,
   out ulong NumberOfBytesWritten
);
```

