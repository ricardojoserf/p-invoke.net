## GetQueuedCompletionStatus

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetQueuedCompletionStatus(
   SafeHandle CompletionPort,
   out uint lpNumberOfBytesTransferred,
   out IntPtr lpCompletionKey,
   out IntPtr lpOverlapped,
   uint dwMilliseconds
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-getqueuedcompletionstatus)
