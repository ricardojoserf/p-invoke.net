## CreateTimerQueueTimer

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateTimerQueueTimer(
   out IntPtr phNewTimer,
   SafeTimerQueueHandle TimerQueue,
   WAITORTIMERCALLBACK Callback,
   IntPtr Parameter,
   uint DueTime,
   uint Period,
   uint Flags
);
```

Microsoft documentation: (TODO)
