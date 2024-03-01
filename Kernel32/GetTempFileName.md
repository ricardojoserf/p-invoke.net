## GetTempFileName

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetTempFileName(
   string lpPathName,
   string lpPrefixString,
   uint uUnique,
   StringBuilder lpTempFileName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-gettempfilenamew)
