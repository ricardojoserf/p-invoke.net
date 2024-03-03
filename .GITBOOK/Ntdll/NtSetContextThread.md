## NtSetContextThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSetContextThread(
   IntPtr hThread,
   ref CONTEXT lpContext
);
```

Microsoft documentation: [Link](https://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FNT%20Objects%2FThread%2FThread%20Context%2FNtSetContextThread.html)
