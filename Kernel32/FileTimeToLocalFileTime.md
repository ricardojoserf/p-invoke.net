## FileTimeToLocalFileTime

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FileTimeToLocalFileTime(
   ref FILETIME lpFileTime,
   out FILETIME lpLocalFileTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-filetimetolocalfiletime)
