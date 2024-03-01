## HeapCreate

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr HeapCreate(
   uint flOptions,
   UIntPtr dwInitialSize,
   UIntPtr dwMaximumSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapcreate)
