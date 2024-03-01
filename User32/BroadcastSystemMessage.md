## BroadcastSystemMessage

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr BroadcastSystemMessage(
   uint flags,
   ref uint pdwRecipients,
   uint uiMessage,
   UIntPtr wParam,
   IntPtr lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-broadcastsystemmessage)
