## Writefileex

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteFileEx(IntPtr hFile,
   [MarshalAs(UnmanagedType.LPArray)] byte[] lpBuffer,
   uint nNumberOfBytesToWrite,
   ref OVERLAPPED lpOverlapped,
   LPOVERLAPPED_COMPLETION_ROUTINE lpCompletionRoutine
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-writefileex)
