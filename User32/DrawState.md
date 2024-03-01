## DrawState

```
[DllImport("user32.dll", SetLastError = true)]
public static extern uint DrawStateA(
   IntPtr hdc,
   IntPtr hbrFore,
   IntPtr qfnCallBack,
   IntPtr lData,
   IntPtr wData,
   int x,
   int y,
   int cx,
   int cy,
   uint fuFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-drawstatea)
