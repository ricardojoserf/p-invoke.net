## CreateIoCompletionPort

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeFileHandle CreateIoCompletionPort(IntPtr FileHandle, IntPtr ExistingCompletionPort, UIntPtr CompletionKey, uint NumberOfConcurrentThreads);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-createiocompletionport)
