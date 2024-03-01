## midiInOpen

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiInOpen(
   out IntPtr lphmi,
   uint uDeviceID,
   IntPtr dwCallback,
   IntPtr dwInstance,
   uint fdwOpen
);
```

[Microsoft documentation](link_to_documentation)
