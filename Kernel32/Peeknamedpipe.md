## Peeknamedpipe

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool PeekNamedPipe(IntPtr hNamedPipe,
   byte[] lpBuffer,
   uint nBufferSize,
   ref uint lpBytesRead,
   ref uint lpTotalBytesAvail,
   ref uint lpBytesLeftThisMessage
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-peeknamedpipe)
