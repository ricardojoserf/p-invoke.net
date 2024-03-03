## SCardEndTransaction

```
[DllImport("winscard.dll", SetLastError = true)]
public static extern int SCardEndTransaction(
   IntPtr hCard,
   uint dwDisposition
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winscard/nf-winscard-scardendtransaction)
