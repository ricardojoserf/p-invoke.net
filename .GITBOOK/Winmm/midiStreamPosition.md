## midiStreamPosition

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiStreamPosition(
   IntPtr hms,
   IntPtr lpmmt,
   uint cbmmt
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midistreamposition)
