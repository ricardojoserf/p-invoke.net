## Reseteven

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ResetEvent(IntPtr hEvent
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-resetevent)
