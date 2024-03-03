## GetThreadContext

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetThreadContext(
   IntPtr hThread,
   ref CONTEXT lpContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getthreadcontext)
