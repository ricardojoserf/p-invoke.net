## GetCurrentPowerPolicies

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool GetCurrentPowerPolicies(
   ref SYSTEM_POWER_POLICY pGlobalPowerPolicy,
   ref SYSTEM_POWER_POLICY pPowerPolicyAc,
   ref SYSTEM_POWER_POLICY pPowerPolicyDc
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-getcurrentpowerpolicies)
