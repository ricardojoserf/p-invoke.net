## Queueuserapc

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool QueueUserAPC(
   IntPtr pfnAPC,
   IntPtr hThread,
   UIntPtr dwData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-queueuserapc)
