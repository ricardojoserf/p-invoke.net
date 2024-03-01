## GetModuleFileName

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern uint GetModuleFileName(
   IntPtr hModule,
   StringBuilder lpFilename,
   uint nSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-getmodulefilenamea)
