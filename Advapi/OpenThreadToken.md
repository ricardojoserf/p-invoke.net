## OpenThreadToken

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool OpenThreadToken(
   IntPtr ThreadHandle,
   uint DesiredAccess,
   bool OpenAsSelf,
   out IntPtr TokenHandle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-openthreadtoken)
