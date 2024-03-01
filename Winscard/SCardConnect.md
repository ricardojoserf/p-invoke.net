## SCardConnect

```
[DllImport("winscard.dll", SetLastError = true)]
public static extern int SCardConnect(
   IntPtr hContext,
   string szReader,
   uint dwShareMode,
   uint dwPreferredProtocols,
   out IntPtr phCard,
   out uint pdwActiveProtocol
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winscard/nf-winscard-scardconnecta)
