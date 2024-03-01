## Module32next

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool Module32Next(IntPtr hSnapshot,
   ref MODULEENTRY32 lpme
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-module32next)
