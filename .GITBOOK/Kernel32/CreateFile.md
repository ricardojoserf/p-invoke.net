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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/fileio/creating-and-opening-files#:~:text=The%20CreateFile%20function%20can%20create,it%20to%20the%20specified%20directory.)
