## midiStreamOpen

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiStreamOpen(
   out IntPtr lphms,
   ref uint puDeviceID,
   uint cMidi,
   IntPtr dwCallback,
   IntPtr dwInstance,
   uint fdwOpen
);
```

Microsoft documentation: (TODO)
