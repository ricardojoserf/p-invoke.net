## GetOverlappedResult

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetOverlappedResult(
   SafeFileHandle hFile,
   ref OVERLAPPED lpOverlapped,
   out uint lpNumberOfBytesTransferred,
   [MarshalAs(UnmanagedType.Bool)] bool bWait
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-getoverlappedresult)
