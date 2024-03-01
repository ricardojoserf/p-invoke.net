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

[Microsoft documentation](link_to_documentation)
