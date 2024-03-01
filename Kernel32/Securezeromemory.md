## Securezeromemory

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SecureZeroMemory(IntPtr ptr,
   UIntPtr cnt
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-securezeromemory)
