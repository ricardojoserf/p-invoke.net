## Openmutex

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr OpenMutex(uint dwDesiredAccess,
   [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle,
   string lpName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-openmutexw)
