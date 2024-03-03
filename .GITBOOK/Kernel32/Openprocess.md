## Openprocess

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr OpenProcess(uint dwDesiredAccess,
   [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle,
   uint dwProcessId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-openprocess)
