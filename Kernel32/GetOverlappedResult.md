## GetOverlappedResult

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetOverlappedResult(
   SafeFileHandle hFile,
   ref OVERLAPPED lpOverlapped,
   out uint lpNumberOfBytesTransferred,
   [MarshalAs(
   UnmanagedType.Bool)] bool bWait
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getoverlappedresult)
