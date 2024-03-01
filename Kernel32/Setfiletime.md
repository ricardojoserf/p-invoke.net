## Setfiletime

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetFileTime(IntPtr hFile,
   [In] ref FILETIME lpCreationTime,
   [In] ref FILETIME lpLastAccessTime,
   [In] ref FILETIME lpLastWriteTime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-setfiletime)
