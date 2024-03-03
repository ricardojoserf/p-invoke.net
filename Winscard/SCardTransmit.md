## SCardTransmit

```csharp
[DllImport("winscard.dll", SetLastError = true)]
public static extern int SCardTransmit(
   IntPtr hCard,
   ref SCARD_IO_REQUEST pioSendPci,
   byte[] pbSendBuffer,
   uint cbSendLength,
   IntPtr pioRecvPci,
   byte[] pbRecvBuffer,
   ref uint pcbRecvLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winscard/nf-winscard-scardtransmit)
