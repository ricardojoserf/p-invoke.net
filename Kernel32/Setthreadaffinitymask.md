## Setthreadaffinitymask

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetThreadAffinityMask(IntPtr hThread,
   UIntPtr dwThreadAffinityMask
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-setthreadaffinitymask)
