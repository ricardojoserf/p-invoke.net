## SetThreadToken

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetThreadToken(
   IntPtr Thread,
   IntPtr Token
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-setthreadtoken)
