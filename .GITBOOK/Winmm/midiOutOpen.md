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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midioutopen)
