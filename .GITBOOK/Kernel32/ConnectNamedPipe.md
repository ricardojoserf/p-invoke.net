## ConnectNamedPipe

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ConnectNamedPipe(
   IntPtr hNamedPipe,
   IntPtr lpOverlapped
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-connectnamedpipe)
