## ToAscii

```
[DllImport("user32.dll", SetLastError = true)]
public static extern int ToAscii(
   uint uVirtKey,
   uint uScanCode,
   byte[] lpKeyState,
   out ushort lpChar,
   uint uFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-toascii)
