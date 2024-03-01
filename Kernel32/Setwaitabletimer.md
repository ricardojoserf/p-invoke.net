## Setwaitabletimer

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetWaitableTimer(IntPtr hTimer,
   [In] ref LARGE_INTEGER pDueTime,
   int lPeriod,
   TimerAPCProc pfnCompletionRoutine,
   IntPtr lpArgToCompletionRoutine,
   [MarshalAs(UnmanagedType.Bool)] bool fResume
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-setwaitabletimer)
