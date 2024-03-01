## Writefile

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteFile(IntPtr hFile,
   [MarshalAs(UnmanagedType.LPArray)] byte[] lpBuffer,
   uint nNumberOfBytesToWrite,
   out uint lpNumberOfBytesWritten,
   IntPtr lpOverlapped
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-writefile)
