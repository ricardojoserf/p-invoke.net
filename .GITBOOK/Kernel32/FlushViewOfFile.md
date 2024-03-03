## FlushViewOfFile

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FlushViewOfFile(
   IntPtr lpBaseAddress,
   uint dwNumberOfBytesToFlush
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-flushviewoffile)
