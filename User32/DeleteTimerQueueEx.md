## DeleteTimerQueueEx

```
[DllImport("kernel32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DeleteTimerQueueEx(
   IntPtr TimerQueue,
   IntPtr CompletionEvent
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/threadpoollegacyapiset/nf-threadpoollegacyapiset-deletetimerqueueex)
