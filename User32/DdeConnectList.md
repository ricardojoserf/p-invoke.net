## DdeConnectList

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeConnectList(
   IntPtr idInst,
   IntPtr hszService,
   IntPtr hszTopic,
   IntPtr hConvList,
   IntPtr pCC
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddeconnectlist)
