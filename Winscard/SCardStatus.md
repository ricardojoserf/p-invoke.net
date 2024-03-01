## SCardStatus

```
[DllImport("winscard.dll", SetLastError = true)]
public static extern int SCardStatus(
   IntPtr hCard,
   byte[] szReaderName,
   ref uint pcchReaderLen,
   out uint pdwState,
   out uint pdwProtocol,
   byte[] pbAtr,
   ref uint pcbAtrLen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winscard/nf-winscard-scardstatusa)
