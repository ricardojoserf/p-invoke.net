## NtSetContextThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSetContextThread(
   IntPtr hThread,
   ref CONTEXT lpContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-ke386setcontextthread)
