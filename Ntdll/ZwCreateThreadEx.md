## ZwCreateThreadEx

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int ZwCreateThreadEx(
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

