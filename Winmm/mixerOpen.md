## mixerOpen

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint mixerOpen(
   out IntPtr phmx,
   uint uMxId,
   IntPtr dwCallback,
   IntPtr dwInstance,
   uint fdwOpen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-mixeropen)
