## waveOutUnprepareHeader

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint waveOutUnprepareHeader(
   IntPtr hwo,
   ref WAVEHDR pwh,
   uint cbwh
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveoutunprepareheader)
