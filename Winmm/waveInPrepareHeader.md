## waveInPrepareHeader

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint waveInPrepareHeader(
   IntPtr hwi,
   ref WAVEHDR pwh,
   uint cbwh
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveinprepareheader)
