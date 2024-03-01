## Process32next

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool Process32Next(
   IntPtr hSnapshot,
   ref PROCESSENTRY32 lppe
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-process32next)
