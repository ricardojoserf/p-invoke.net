## GetProcessAffinityMask

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetProcessAffinityMask(
   IntPtr hProcess,
   out IntPtr lpProcessAffinityMask,
   out IntPtr lpSystemAffinityMask
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocessaffinitymask)
