## Lockfileex

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LockFileEx(IntPtr hFile,
   uint dwFlags,
   uint dwReserved,
   uint nNumberOfBytesToLockLow,
   uint nNumberOfBytesToLockHigh,
   ref OVERLAPPED lpOverlapped
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-lockfileex)
