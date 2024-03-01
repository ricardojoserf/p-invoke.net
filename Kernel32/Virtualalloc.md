## Virtualalloc

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.LPArray, SizeParamIndex = 1)]
public static extern IntPtr VirtualAlloc(IntPtr lpAddress,
   UIntPtr dwSize,
   uint flAllocationType,
   uint flProtect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-virtualalloc)
