## DdeAbandonTransaction

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeAbandonTransaction(
   uint idInst,
   IntPtr hConv,
   uint idTransaction
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddeabandontransaction)
