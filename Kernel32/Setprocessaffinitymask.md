## Setprocessaffinitymask

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetProcessAffinityMask(IntPtr hProcess,
   UIntPtr dwProcessAffinityMask
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-setprocessaffinitymask)
