## Openthread

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr OpenThread(uint dwDesiredAccess,
   [MarshalAs(UnmanagedType.Bool)] bool bInheritHandle,
   uint dwThreadId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-openthread)
