## timeSetEvent

```csharp
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint timeSetEvent(
   uint uDelay,
   uint uResolution,
   IntPtr lpTimeProc,
   IntPtr dwUser,
   uint fuEvent
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/dd757634(v=vs.85)#:~:text=The%20timeSetEvent%20function%20starts%20a,Note%20This%20function%20is%20obsolete.)
