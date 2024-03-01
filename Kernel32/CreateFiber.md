## CreateFiber

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr CreateFiber(
   int dwStackSize,
   LPFIBER_START_ROUTINE lpStartAddress,
   IntPtr lpParameter
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createfiber)
