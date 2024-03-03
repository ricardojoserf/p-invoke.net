## NtCreateFile

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtCreateFile(
   out IntPtr FileHandle,
   FileAccess DesiredAccess,
   ref OBJECT_ATTRIBUTES ObjectAttributes,
   ref IO_STATUS_BLOCK IoStatusBlock,
   long AllocationSize,
   uint FileAttributes,
   FileShare ShareAccess,
   FileDisposition CreateDisposition,
   FileOptions CreateOptions,
   IntPtr EaBuffer,
   uint EaLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntcreatefile)
