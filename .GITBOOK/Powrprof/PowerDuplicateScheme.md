## PowerDuplicateScheme

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool PowerDuplicateScheme(
   IntPtr RootPowerKey,
   ref IntPtr DestinationPowerKey
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-powerduplicatescheme)
