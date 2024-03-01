## NetScheduleJobAdd

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetScheduleJobAdd(
   string Servername,
   IntPtr Buffer,
   out uint JobId
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmapibuf/nf-lmapibuf-netschedulejobadd)
