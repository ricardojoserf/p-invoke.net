## DdePostAdvise

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdePostAdvise(
   IntPtr idInst,
   IntPtr hszItem,
   IntPtr hszTopic
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddepostadvise)
