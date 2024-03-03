## midiStreamOpen

```csharp
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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midistreamopen)
