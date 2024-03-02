## waveOutGetDevCaps

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint waveOutGetDevCaps(
   uint uDeviceID,
   ref WAVEOUTCAPS pwoc,
   uint cbwoc
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveoutgetdevcaps)
