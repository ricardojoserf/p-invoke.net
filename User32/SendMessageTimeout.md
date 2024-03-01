## SendMessageTimeout

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr SendMessageTimeout(
   IntPtr hWnd,
   uint Msg,
   IntPtr wParam,
   StringBuilder lParam,
   uint fuFlags,
   uint uTimeout,
   out IntPtr lpdwResult
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-sendmessagetimeouta)
