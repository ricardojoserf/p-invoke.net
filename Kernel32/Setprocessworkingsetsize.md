## Setprocessworkingsetsize

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetProcessWorkingSetSize(IntPtr hProcess,
   IntPtr dwMinimumWorkingSetSize,
   IntPtr dwMaximumWorkingSetSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-setprocessworkingsetsize)
