## Openevent

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr OpenEvent(uint dwDesiredAccess,
   [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle,
   string lpName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-openeventw)
