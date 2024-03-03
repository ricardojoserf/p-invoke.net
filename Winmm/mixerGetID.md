## mixerGetID

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint mixerGetID(
   IntPtr hmxobj,
   ref uint puMxId,
   uint fdwId
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-mixergetid)
