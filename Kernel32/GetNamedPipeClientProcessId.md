## GetNamedPipeClientProcessId

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetNamedPipeClientProcessId(
   SafePipeHandle hNamedPipe,
   out uint clientProcessId
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-getnamedpipeclientprocessid)
