## MsgWaitForMultipleObjectsEx

```
[DllImport("user32.dll", SetLastError = true)]
public static extern uint MsgWaitForMultipleObjectsEx(
   uint nCount,
   IntPtr[] pHandles,
   uint dwMilliseconds,
   uint dwWakeMask,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-msgwaitformultipleobjectsex)
