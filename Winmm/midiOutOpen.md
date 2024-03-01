## midiOutOpen

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiOutOpen(
   out IntPtr lphmo,
   uint uDeviceID,
   IntPtr dwCallback,
   IntPtr dwInstance,
   uint fdwOpen
);
```

[Microsoft documentation](TODO)
