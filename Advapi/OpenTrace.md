## OpenTrace

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint OpenTrace(
   ref TRACEHANDLE TraceHandle,
   string InstanceName,
   ref EVENT_TRACE_PROPERTIES Properties
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-opentracea)
