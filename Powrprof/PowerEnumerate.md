## PowerEnumerate

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool PowerEnumerate(
   IntPtr RootPowerKey,
   ref Guid SchemeGuid,
   ref Guid SubGroupOfPowerSetting,
   uint AccessFlags,
   uint Index,
   ref Guid SettingGuid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-powerenumerate)
