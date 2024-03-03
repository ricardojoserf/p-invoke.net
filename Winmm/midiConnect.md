## midiConnect

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint midiConnect(
   IntPtr hmi,
   IntPtr hmo,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-midiconnect)
