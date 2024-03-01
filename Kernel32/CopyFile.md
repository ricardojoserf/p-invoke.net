## CopyFile

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CopyFile(
   string lpExistingFileName,
   string lpNewFileName,
   [MarshalAs(UnmanagedType.Bool)] bool bFailIfExists
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-copyfile)
