## Virtualprotectex

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool VirtualProtectEx(IntPtr hProcess,
   IntPtr lpAddress,
   UIntPtr dwSize,
   uint flNewProtect,
   out uint lpflOldProtect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-virtualprotectex)
