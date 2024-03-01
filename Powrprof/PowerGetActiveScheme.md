## PowerGetActiveScheme

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern uint PowerGetActiveScheme(
   IntPtr UserRootPowerKey,
   ref IntPtr ActivePolicyGuid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-powergetactivescheme)
