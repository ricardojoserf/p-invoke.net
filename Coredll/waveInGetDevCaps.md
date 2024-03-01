## waveInGetDevCaps

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern uint waveInGetDevCaps(
   uint uDeviceID,
   ref WAVEINCAPS pwic,
   uint cbwic
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveingetdevcaps)
