## CreateFile

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeFileHandle CreateFile(
   string lpFileName,
   uint dwDesiredAccess,
   uint dwShareMode,
   IntPtr lpSecurityAttributes,
   uint dwCreationDisposition,
   uint dwFlagsAndAttributes,
   IntPtr hTemplateFile
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-createfile)
