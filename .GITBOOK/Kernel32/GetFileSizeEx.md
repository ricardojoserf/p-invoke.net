## GetFileSizeEx

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetFileSizeEx(
   SafeFileHandle hFile,
   out ulong lpFileSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfilesizeex)
