## Remotedebugger

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool RemoteDebuggerPresent(IntPtr hProcess,
   [MarshalAs(UnmanagedType.Bool)] ref bool pbDebuggerPresent
);
```

