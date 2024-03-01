## ToAsciiEx

```
[DllImport("user32.dll", SetLastError = true)]
public static extern int ToAsciiEx(
   uint uVirtKey,
   uint uScanCode,
   byte[] lpKeyState,
   out ushort lpChar,
   uint uFlags,
   IntPtr hkl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-toasciiex)
