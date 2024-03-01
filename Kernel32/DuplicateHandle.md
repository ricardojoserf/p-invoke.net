## DuplicateHandle

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DuplicateHandle(
   IntPtr hSourceProcessHandle,
   IntPtr hSourceHandle,
   IntPtr hTargetProcessHandle,
   out IntPtr lpTargetHandle,
   uint dwDesiredAccess,
   [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle,
   uint dwOptions
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/handleapi/nf-handleapi-duplicatehandle)
