## CreateNamedPipe

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafePipeHandle CreateNamedPipe(
   string lpName,
   uint dwOpenMode,
   uint dwPipeMode,
   uint nMaxInstances,
   uint nOutBufferSize,
   uint nInBufferSize,
   uint nDefaultTimeOut,
   IntPtr lpSecurityAttributes
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-createnamedpipew)
