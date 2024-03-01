## PowerReadFriendlyName

```
[DllImport("powrprof.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern uint PowerReadFriendlyName(
   IntPtr RootPowerKey,
   ref Guid SchemeGuid,
   ref Guid SubGroupOfPowerSetting,
   ref Guid PowerSetting,
   StringBuilder Buffer,
   ref uint BufferSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-powerreadfriendlyname)
