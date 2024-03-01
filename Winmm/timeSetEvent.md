## timeSetEvent

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint timeSetEvent(
   uint uDelay,
   uint uResolution,
   IntPtr lpTimeProc,
   IntPtr dwUser,
   uint fuEvent
);
```

[Microsoft documentation](link_to_documentation)
