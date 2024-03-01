## GetNamedPipeClientProcessId

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetNamedPipeClientProcessId(
   SafePipeHandle hNamedPipe,
   out uint clientProcessId
);
```

Microsoft documentation: (TODO)
