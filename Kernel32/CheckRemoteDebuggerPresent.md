## CheckRemoteDebuggerPresent

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckRemoteDebuggerPresent(
   IntPtr hProcess,
   [MarshalAs(UnmanagedType.Bool)] ref bool pbDebuggerPresent
);
```

Microsoft documentation: (TODO)
