## PostThreadMessage

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool PostThreadMessage(
   uint idThread,
   uint Msg,
   IntPtr wParam,
   IntPtr lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-postthreadmessagea)
