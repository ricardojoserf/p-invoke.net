## Virtualprotect

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool VirtualProtect(IntPtr lpAddress,
   UIntPtr dwSize,
   uint flNewProtect,
   out uint lpflOldProtect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-virtualprotect)
