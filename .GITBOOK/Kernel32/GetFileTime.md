## GetFileTime

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetFileTime(
   SafeFileHandle hFile,
   ref FILETIME lpCreationTime,
   ref FILETIME lpLastAccessTime,
   ref FILETIME lpLastWriteTime
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfiletime)
