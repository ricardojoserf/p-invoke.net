## Waitfordebugevent

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WaitForDebugEvent([Out] out DEBUG_EVENT lpDebugEvent,
   uint dwMilliseconds
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-waitfordebugevent)
