## Waitcommevent

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WaitCommEvent(IntPtr hFile,
   IntPtr lpEvtMask,
   IntPtr lpOverlapped
);
```

Microsoft documentation: (TODO)
