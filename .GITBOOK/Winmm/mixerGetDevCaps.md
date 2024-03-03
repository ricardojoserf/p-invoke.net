## mixerGetDevCaps

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint mixerGetDevCaps(
   uint uMxId,
   ref MIXERCAPS pmxcaps,
   uint cbmxcaps
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-mixergetdevcaps)
