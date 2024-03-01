## NtSetContextThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSetContextThread(
   IntPtr hThread,
   ref CONTEXT lpContext
);
```

Microsoft documentation: (TODO)
