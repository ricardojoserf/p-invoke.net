## timeGetSystemTime

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint timeGetSystemTime(
   IntPtr pmmt,
   uint cbmmt
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/timeapi/#:~:text=The%20timeGetSystemTime%20function%20retrieves%20the%20system%20time%2C%20in%20milliseconds.&text=The%20timeGetTime%20function%20retrieves%20the,elapsed%20since%20Windows%20was%20started.)
