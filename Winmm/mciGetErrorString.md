## mciGetErrorString

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint mciGetErrorString(
   uint fdwError,
   StringBuilder lpszErrorText,
   uint cchErrorText
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/dd757158(v=vs.85))
