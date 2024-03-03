## OpenProcessToken

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool OpenProcessToken(
   IntPtr ProcessHandle,
   uint DesiredAccess,
   out IntPtr TokenHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-openprocesstoken)
