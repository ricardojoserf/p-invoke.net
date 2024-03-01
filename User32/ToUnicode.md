## ToUnicode

```
[DllImport("user32.dll", SetLastError = true)]
public static extern int ToUnicode(
   uint wVirtKey,
   uint wScanCode,
   byte[] lpKeyState,
   ushort[] pwszBuff,
   int cchBuff,
   uint wFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-tounicode)
