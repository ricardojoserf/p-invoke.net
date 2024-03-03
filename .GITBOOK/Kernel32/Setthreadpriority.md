## Setthreadpriority

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetThreadPriority(IntPtr hThread,
   int nPriority
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-setthreadpriority)
