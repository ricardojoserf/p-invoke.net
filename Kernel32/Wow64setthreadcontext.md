## Wow64setthreadcontext

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool Wow64SetThreadContext(
   IntPtr hThread,
   [In] ref CONTEXT lpContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wow64apiset/nf-wow64apiset-wow64setthreadcontext)
