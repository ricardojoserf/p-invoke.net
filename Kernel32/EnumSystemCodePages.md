## EnumSystemCodePages

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumSystemCodePages(EnumCodePageProc lpCodePageEnumProc, uint dwFlags);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumsystemcodepages)
