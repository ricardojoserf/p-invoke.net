## Setsystemfilecachesize

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetSystemFileCacheSize(IntPtr hFile,
   int dwMinimumFileCacheSize,
   int dwMaximumFileCacheSize,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-setsystemfilecachesize)
