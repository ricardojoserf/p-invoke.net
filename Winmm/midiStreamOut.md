## midiStreamOut

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiStreamOut(
   IntPtr hms,
   IntPtr pmh,
   uint cbmh
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midistreamout)
