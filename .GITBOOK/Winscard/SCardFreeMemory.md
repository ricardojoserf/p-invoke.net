## SCardFreeMemory

```
[DllImport("winscard.dll", SetLastError = true)]
public static extern int SCardFreeMemory(
   IntPtr hContext,
   IntPtr pvMem
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winscard/nf-winscard-scardfreememory)
