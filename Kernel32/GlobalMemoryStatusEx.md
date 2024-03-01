## GlobalMemoryStatusEx

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GlobalMemoryStatusEx(
   ref MEMORYSTATUSEX lpBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-globalmemorystatusex)
