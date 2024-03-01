## Readfilescatter

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReadFileScatter(IntPtr hFile,
   [In] FILE_SEGMENT_ELEMENT[] aSegmentArray,
   uint nNumberOfBytesToRead,
   IntPtr lpReserved,
   ref OVERLAPPED lpOverlapped
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-readfilescatter)
