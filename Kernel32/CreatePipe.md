## CreatePipe

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreatePipe(
   out SafeFileHandle hReadPipe,
   out SafeFileHandle hWritePipe,
   IntPtr lpPipeAttributes,
   uint nSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-createpipe)
