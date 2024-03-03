## Setprocessaffinitymask

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetProcessAffinityMask(IntPtr hProcess,
   UIntPtr dwProcessAffinityMask
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setprocessaffinitymask)
