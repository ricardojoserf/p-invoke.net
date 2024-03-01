## CreateMutex

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeWaitHandle CreateMutex(
   IntPtr lpMutexAttributes,
   [MarshalAs(UnmanagedType.Bool)] bool bInitialOwner,
   string lpName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-createmutexw)
