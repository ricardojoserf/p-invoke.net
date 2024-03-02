## CreateDirectory

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateDirectory(
   string lpPathName,
   IntPtr lpSecurityAttributes
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-createdirectorya)
