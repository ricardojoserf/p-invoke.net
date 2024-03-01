## Readfileex

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReadFileEx(
   IntPtr hFile,
   [Out] byte[] lpBuffer,
   uint nNumberOfBytesToRead,
   ref OVERLAPPED lpOverlapped,
   LPOVERLAPPED_COMPLETION_ROUTINE lpCompletionRoutine
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-readfileex)
