## SCardListReaders

```
[DllImport("winscard.dll", SetLastError = true)]
public static extern int SCardListReaders(
   IntPtr hContext,
   byte[] mszReaders,
   ref uint pcchReaders
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winscard/nf-winscard-scardlistreadersa)
