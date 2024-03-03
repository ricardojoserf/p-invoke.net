## WTSSendMessage

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSSendMessage(
   IntPtr hServer,
   int SessionId,
   string pTitle,
   int TitleLength,
   string pMessage,
   int MessageLength,
   int Style,
   int Timeout,
   ref int pResponse,
   bool bWait
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtssendmessagea)
