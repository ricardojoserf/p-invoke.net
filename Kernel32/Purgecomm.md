## Purgecomm

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool PurgeComm(IntPtr hFile,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-purgecomm)
