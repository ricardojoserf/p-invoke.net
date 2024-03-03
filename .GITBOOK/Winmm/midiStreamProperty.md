## midiStreamProperty

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiStreamProperty(
   IntPtr hms,
   IntPtr lppropdata,
   uint dwProperty
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midistreamproperty)
