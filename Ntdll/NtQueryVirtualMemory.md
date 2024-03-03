## NtQueryVirtualMemory

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryVirtualMemory(
   IntPtr ProcessHandle,
   IntPtr BaseAddress,
   MEMORY_INFORMATION_CLASS MemoryInformationClass,
   IntPtr MemoryInformation,
   uint MemoryInformationLength,
   out uint ReturnLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-virtualqueryex)
