## ReadPwrScheme

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool ReadPwrScheme(
   IntPtr UserRootPowerKey,
   ref Guid SchemeGuid,
   ref IntPtr pScheme
);
```

[Microsoft documentation](TODO)
