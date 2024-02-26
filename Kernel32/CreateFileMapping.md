## CreateFileMapping

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeFileHandle CreateFileMapping(IntPtr hFile, IntPtr lpFileMappingAttributes, uint flProtect, uint dwMaximumSizeHigh, uint dwMaximumSizeLow, string lpName);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-createfilemappingw)
