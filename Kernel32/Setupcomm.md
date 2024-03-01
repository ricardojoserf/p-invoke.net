## Setupcomm

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetupComm(IntPtr hFile,
   uint dwInQueue,
   uint dwOutQueue
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setupcomm)
