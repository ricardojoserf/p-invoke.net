## waveInPrepareHeader

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern uint waveInPrepareHeader(
   IntPtr hwi,
   ref WAVEHDR pwh,
   uint cbwh
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveinprepareheader)
