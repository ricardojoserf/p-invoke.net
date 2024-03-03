## waveOutOpen

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint waveOutOpen(
   out IntPtr phwo,
   uint uDeviceID,
   ref WAVEFORMATEX pwfx,
   IntPtr dwCallback,
   IntPtr dwInstance,
   uint fdwOpen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveoutopen)
