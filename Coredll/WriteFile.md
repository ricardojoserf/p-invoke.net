## WriteFile

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern int WriteFile(
   IntPtr hFile,
   byte[] lpBuffer,
   uint nNumberOfBytesToWrite,
   ref uint lpNumberOfBytesWritten,
   IntPtr lpOverlapped
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-writefile)
