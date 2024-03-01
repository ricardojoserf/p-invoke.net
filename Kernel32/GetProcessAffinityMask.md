## GetProcessAffinityMask

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetProcessAffinityMask(
   IntPtr hProcess,
   out IntPtr lpProcessAffinityMask,
   out IntPtr lpSystemAffinityMask
);
```

[Microsoft documentation](TODO)
