## Process32first

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool Process32First(IntPtr hSnapshot,
   ref PROCESSENTRY32 lppe
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-process32first)
