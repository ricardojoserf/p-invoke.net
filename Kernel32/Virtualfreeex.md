## Virtualfreeex

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool VirtualFreeEx(IntPtr hProcess,
   IntPtr lpAddress,
   UIntPtr dwSize,
   uint dwFreeType
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-virtualfreeex)
