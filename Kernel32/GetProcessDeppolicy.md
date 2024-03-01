## GetProcessDeppolicy

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetProcessDEPPolicy(IntPtr hProcess,
   out uint lpFlags,
   [MarshalAs(UnmanagedType.Bool)] out bool lpPermanent
);
```

[Microsoft documentation](TODO)
