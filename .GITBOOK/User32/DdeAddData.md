## DdeAddData

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeAddData(
   IntPtr hData,
   IntPtr pSrc,
   uint cb,
   uint cbOff
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddeadddata)
