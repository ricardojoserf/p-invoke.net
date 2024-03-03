## TraceEvent

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint TraceEvent(
   [In] TRACEHANDLE SessionHandle,
   [In] ref EVENT_TRACE_HEADER EventTrace
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-traceevent)
