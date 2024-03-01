## CopyFileEx

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CopyFileEx(
   string lpExistingFileName,
   string lpNewFileName,
   LPOVERLAPPED lpProgressRoutine,
   IntPtr lpData,
   ref int pbCancel,
   CopyFileFlags dwCopyFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-copyfileex)
