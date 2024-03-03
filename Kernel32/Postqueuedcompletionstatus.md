## Postqueuedcompletionstatus

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool PostQueuedCompletionStatus(IntPtr CompletionPort,
   uint dwNumberOfBytesTransferred,
   UIntPtr dwCompletionKey,
   IntPtr lpOverlapped
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ioapiset/nf-ioapiset-postqueuedcompletionstatus)
