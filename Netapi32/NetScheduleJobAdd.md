## NetScheduleJobAdd

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetScheduleJobAdd(
   string Servername,
   IntPtr Buffer,
   out uint JobId
);
```

[Microsoft documentation](TODO)
