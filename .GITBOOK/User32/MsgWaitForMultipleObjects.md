## MsgWaitForMultipleObjects

```
[DllImport("user32.dll", SetLastError = true)]
public static extern uint MsgWaitForMultipleObjects(
   uint nCount,
   IntPtr[] pHandles,
   bool fWaitAll,
   uint dwMilliseconds,
   uint dwWakeMask
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-msgwaitformultipleobjects)
