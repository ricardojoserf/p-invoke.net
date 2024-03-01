## AssignProcessToJobObject

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AssignProcessToJobObject(
   IntPtr hJob,
   IntPtr hProcess
);
```

Microsoft documentation: (TODO)
