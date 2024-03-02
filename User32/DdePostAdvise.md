## DdePostAdvise

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdePostAdvise(
   IntPtr idInst,
   IntPtr hszItem,
   IntPtr hszTopic
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddepostadvise)
