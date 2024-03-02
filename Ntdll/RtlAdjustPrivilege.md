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

Microsoft documentation: [Link](https://ntdoc.m417z.com/rtladjustprivilege)
