## CreateFiber

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr CreateFiber(
   int dwStackSize,
   LPFIBER_START_ROUTINE lpStartAddress,
   IntPtr lpParameter
);
```

Microsoft documentation: (TODO)
