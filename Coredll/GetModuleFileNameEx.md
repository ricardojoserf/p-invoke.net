## GetModuleFileNameEx

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern uint GetModuleFileNameEx(
   IntPtr hProcess,
   IntPtr hModule,
   StringBuilder lpFilename,
   uint nSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-getmodulefilenameexa)
