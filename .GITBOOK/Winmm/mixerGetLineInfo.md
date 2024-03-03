## mixerGetLineInfo

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint mixerGetLineInfo(
   uint uMxId,
   ref MIXERLINE pmxl,
   uint fdwInfo
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-mixergetlineinfo)
