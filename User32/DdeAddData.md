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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddeadddata)
