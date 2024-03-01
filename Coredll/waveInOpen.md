## waveInOpen

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern uint waveInOpen(
   out IntPtr phwi,
   uint uDeviceID,
   ref WAVEFORMATEX pwfx,
   IntPtr dwCallback,
   IntPtr dwInstance,
   uint fdwOpen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveinopen)
