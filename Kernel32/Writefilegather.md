## Writefilegather

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteFileGather(IntPtr hFile,
   FILE_SEGMENT_ELEMENT[] aSegmentArray,
   uint nNumberOfBytesToWrite,
   IntPtr lpReserved,
   ref OVERLAPPED lpOverlapped
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-writefilegather)
