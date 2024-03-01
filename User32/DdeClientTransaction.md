## DdeClientTransaction

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeClientTransaction(
   IntPtr pData,
   uint cbData,
   IntPtr hConv,
   IntPtr hszItem,
   uint wFmt,
   uint wType,
   uint dwTimeout,
   IntPtr pdwResult
);
```

Microsoft documentation: (TODO)
