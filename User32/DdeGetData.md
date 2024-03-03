## DdeGetData

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeGetData(
   IntPtr hData,
   byte[] pDst,
   uint cbMax,
   uint cbOff
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddegetdata)
