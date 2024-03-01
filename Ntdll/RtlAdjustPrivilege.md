## RtlAdjustPrivilege

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int RtlAdjustPrivilege(
   uint Privilege,
   bool Enable,
   bool CurrentThread,
   out bool Enabled
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ntifs/nf-ntifs-rtladjustprivilege)
