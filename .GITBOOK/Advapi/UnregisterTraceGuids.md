## UnregisterTraceGuids

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint UnregisterTraceGuids(
   [In] TRACEHANDLE RegistrationHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-unregistertraceguids)
