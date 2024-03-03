## midiOutGetDevCaps

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiOutGetDevCaps(
   uint uDeviceID,
   ref MIDIOUTCAPS pmoc,
   uint cbmoc
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midioutgetdevcaps)
