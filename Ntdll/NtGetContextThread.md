## NtGetContextThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtGetContextThread(
   IntPtr hThread,
   ref CONTEXT lpContext
);
```

Microsoft documentation: [Link](https://ntdoc.m417z.com/ntgetcontextthread)
