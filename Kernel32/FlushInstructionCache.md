## FlushInstructionCache

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FlushInstructionCache(
   IntPtr hProcess,
   IntPtr lpBaseAddress,
   uint dwSize
);
```

[Microsoft documentation](TODO)
