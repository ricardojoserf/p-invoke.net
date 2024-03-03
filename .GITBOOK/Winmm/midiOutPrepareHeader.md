## midiOutPrepareHeader

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiOutPrepareHeader(
   IntPtr hmo,
   IntPtr pmhdr,
   uint cbmhdr
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midioutprepareheader)
