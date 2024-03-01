## DevicePowerState

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern uint DevicePowerState(
   IntPtr hDevice,
   PowerState po,
   ref int pdwState
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/nlmsprep/nf-nlmsprep-devicepowerstate)
