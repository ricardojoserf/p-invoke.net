## CreateWaitableTimer

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeWaitHandle CreateWaitableTimer(
   IntPtr lpTimerAttributes,
   [MarshalAs(UnmanagedType.Bool)] bool bManualReset,
   string lpTimerName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-createwaitabletimerw)
