## midiInGetDevCaps

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiInGetDevCaps(
   uint uDeviceID,
   ref MIDIINCAPS pmic,
   uint cbmic
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midiingetdevcaps)
