## GetMessage

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetMessage(
   out MSG lpMsg,
   IntPtr hWnd,
   uint wMsgFilterMin,
   uint wMsgFilterMax
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getmessage)
