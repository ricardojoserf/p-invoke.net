## GetFullPathName

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetFullPathName(
   string lpFileName,
   uint nBufferLength,
   StringBuilder lpBuffer,
   IntPtr lpFilePart
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfullpathnamew)
