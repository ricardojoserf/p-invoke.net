## IsWow64Process

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool IsWow64Process(
   IntPtr hProcess,
   out bool Wow64Process
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wow64apiset/nf-wow64apiset-iswow64process)
