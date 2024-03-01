## SCardEstablishContext

```
[DllImport("winscard.dll", SetLastError = true)]
public static extern int SCardEstablishContext(
   uint dwScope,
   IntPtr pvReserved1,
   IntPtr pvReserved2,
   out IntPtr phContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winscard/nf-winscard-scardestablishcontext)
