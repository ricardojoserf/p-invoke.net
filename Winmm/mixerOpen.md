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

[Microsoft documentation](link_to_documentation)
