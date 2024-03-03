## mixerGetLineControls

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint mixerGetLineControls(
   IntPtr hmxobj,
   ref MIXERLINECONTROLS pmxlc,
   uint fdwControls
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-mixergetlinecontrols)
