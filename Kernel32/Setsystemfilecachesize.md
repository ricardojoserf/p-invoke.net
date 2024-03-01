## Setsystemfilecachesize

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetSystemFileCacheSize(IntPtr hFile,
   int dwMinimumFileCacheSize,
   int dwMaximumFileCacheSize,
   uint dwFlags
);
```

Microsoft documentation: (TODO)
