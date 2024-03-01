## CreateFile

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern IntPtr CreateFile(
   string lpFileName,
   FileAccess dwDesiredAccess,
   FileShare dwShareMode,
   IntPtr lpSecurityAttributes,
   FileMode dwCreationDisposition,
   FileAttributes dwFlagsAndAttributes,
   IntPtr hTemplateFile
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-createfilea)
