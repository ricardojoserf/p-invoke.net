## DdeGetData

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeGetData(
   IntPtr hData,
   byte[] pDst,
   uint cbMax,
   uint cbOff
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddegetdata)
