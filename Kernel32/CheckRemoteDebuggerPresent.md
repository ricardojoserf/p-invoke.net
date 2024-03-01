## CheckRemoteDebuggerPresent

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckRemoteDebuggerPresent(
   IntPtr hProcess,
   [MarshalAs(UnmanagedType.Bool)] ref bool pbDebuggerPresent
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-checkremotedebuggerpresent)
