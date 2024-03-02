## Waitcommevent

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WaitCommEvent(IntPtr hFile,
   IntPtr lpEvtMask,
   IntPtr lpOverlapped
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-waitcommevent)
