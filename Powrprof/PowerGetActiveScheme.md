## PowerGetActiveScheme

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern uint PowerGetActiveScheme(
   IntPtr UserRootPowerKey,
   ref IntPtr ActivePolicyGuid
);
```

[Microsoft documentation](TODO)
