## NetScheduleJobAdd

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetScheduleJobAdd(
   string Servername,
   IntPtr Buffer,
   out uint JobId
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmat/nf-lmat-netschedulejobadd)
