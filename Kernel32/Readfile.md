## Readfile

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReadFile(IntPtr hFile,
   [Out] byte[] lpBuffer,
   uint nNumberOfBytesToRead,
   out uint lpNumberOfBytesRead,
   IntPtr lpOverlapped
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-readfile)
