## NtAllocateVirtualMemory

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtAllocateVirtualMemory(
   IntPtr ProcessHandle,
   ref IntPtr BaseAddress,
   uint ZeroBits,
   ref uint RegionSize,
   uint AllocationType,
   uint Protect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/ntifs/nf-ntifs-ntallocatevirtualmemory)
