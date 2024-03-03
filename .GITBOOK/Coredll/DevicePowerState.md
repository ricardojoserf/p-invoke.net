## DevicePowerState

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern uint DevicePowerState(
   IntPtr hDevice,
   PowerState po,
   ref int pdwState
);
```

