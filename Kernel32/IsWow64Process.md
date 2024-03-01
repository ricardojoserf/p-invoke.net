## IsWow64Process

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool IsWow64Process(
   IntPtr hProcess,
   out bool Wow64Process
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-iswow64process)
