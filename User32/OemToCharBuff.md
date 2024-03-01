## OemToCharBuff

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool OemToCharBuff(
   string lpszSrc,
   StringBuilder lpszDst,
   uint cchDstLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-oemtocharbuffw)
