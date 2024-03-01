## BroadcastSystemMessageEx

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr BroadcastSystemMessageEx(
   uint flags,
   ref uint pdwRecipients,
   uint uiMessage,
   UIntPtr wParam,
   IntPtr lParam,
   ref BSMINFO pBSMInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-broadcastsystemmessageexw)
