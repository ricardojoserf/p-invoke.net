## DdeConnect

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeConnect(
   IntPtr idInst,
   IntPtr hszService,
   IntPtr hszTopic,
   IntPtr pCC
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddeconnect)
