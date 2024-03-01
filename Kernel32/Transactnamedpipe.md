## Transactnamedpipe

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool TransactNamedPipe(IntPtr hNamedPipe,
   IntPtr lpInBuffer,
   uint nInBufferSize,
   IntPtr lpOutBuffer,
   uint nOutBufferSize,
   out uint lpBytesRead,
   IntPtr lpOverlapped
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-transactnamedpipe)
