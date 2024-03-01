## NtCreateThreadEx

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtCreateThreadEx(
   out IntPtr ThreadHandle,
   uint DesiredAccess,
   IntPtr ObjectAttributes,
   IntPtr ProcessHandle,
   IntPtr lpStartAddress,
   IntPtr lpParameter,
   bool CreateSuspended,
   uint StackZeroBits,
   uint SizeOfStackCommit,
   uint SizeOfStackReserve,
   IntPtr lpBytesBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntcreatethreadex)
