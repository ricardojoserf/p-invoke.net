## PeekMessage

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool PeekMessage(
   out MSG lpMsg,
   IntPtr hWnd,
   uint wMsgFilterMin,
   uint wMsgFilterMax,
   uint wRemoveMsg
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-peekmessagea)
