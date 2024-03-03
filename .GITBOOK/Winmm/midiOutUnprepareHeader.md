## midiOutUnprepareHeader

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiOutUnprepareHeader(
   IntPtr hmo,
   IntPtr pmhdr,
   uint cbmhdr
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midioutunprepareheader)
