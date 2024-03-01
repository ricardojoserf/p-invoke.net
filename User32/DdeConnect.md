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

Microsoft documentation: (TODO)
