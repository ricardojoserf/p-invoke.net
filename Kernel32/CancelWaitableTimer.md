## CancelWaitableTimer

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CancelWaitableTimer(
   IntPtr hTimer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-cancelwaitabletimer)
