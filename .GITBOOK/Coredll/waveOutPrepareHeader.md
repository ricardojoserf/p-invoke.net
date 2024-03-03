## waveOutPrepareHeader

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern uint waveOutPrepareHeader(
   IntPtr hwo,
   ref WAVEHDR pwh,
   uint cbwh
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveoutprepareheader)
