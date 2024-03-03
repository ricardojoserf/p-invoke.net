## DeleteTimerQueue

```csharp
[DllImport("kernel32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DeleteTimerQueue(
   IntPtr TimerQueue
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/threadpoollegacyapiset/nf-threadpoollegacyapiset-deletetimerqueue)
