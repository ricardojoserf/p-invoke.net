## Setnamedpipehandlestate

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetNamedPipeHandleState(IntPtr hNamedPipe,
   [In,
   Out] ref uint lpMode,
   IntPtr lpMaxCollectionCount,
   IntPtr lpCollectDataTimeout
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/namedpipeapi/nf-namedpipeapi-setnamedpipehandlestate)
