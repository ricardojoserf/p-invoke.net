## CreateTimerQueueTimer

```csharp
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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/threadpoollegacyapiset/nf-threadpoollegacyapiset-createtimerqueuetimer)
