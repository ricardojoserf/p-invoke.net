## SendMessage

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern IntPtr SendMessage(
   IntPtr hWnd,
   uint Msg,
   IntPtr wParam,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-sendmessage)
