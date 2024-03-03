## CheckRemoteDebuggerPresent

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckRemoteDebuggerPresent(
   IntPtr hProcess,
   [MarshalAs(UnmanagedType.Bool)] ref bool pbDebuggerPresent
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/debugapi/nf-debugapi-checkremotedebuggerpresent)
