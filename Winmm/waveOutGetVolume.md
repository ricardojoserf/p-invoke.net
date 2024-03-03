## waveOutGetVolume

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint waveOutGetVolume(
   IntPtr hwo,
   out uint pdwVolume
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-waveoutgetvolume)
