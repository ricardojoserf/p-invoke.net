## mciSendString

```
[DllImport("winmm.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern uint mciSendString(
   string lpszCommand,
   StringBuilder lpszReturnString,
   uint cchReturn,
   IntPtr hwndCallback
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/dd757161(v=vs.85))
