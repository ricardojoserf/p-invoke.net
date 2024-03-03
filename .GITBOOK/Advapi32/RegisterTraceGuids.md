## RegisterTraceGuids

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint RegisterTraceGuids(
   [In] TRACE_GUID_REGISTRATION[] RequestAddress,
   [In] IntPtr RequestContext,
   [In] ref Guid ControlGuid,
   uint GuidCount,
   [In,
   Out] ref REGHANDLE TraceHandle,
   [In] string MofImagePath,
   [In] string MofResourceName,
   [In,
   Out] ref TRACEHANDLE LogfileHandle
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-registertraceguidsa)
