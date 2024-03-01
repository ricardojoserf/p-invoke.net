## SB_GETTEXT

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int SB_GETTEXT(
   IntPtr hwnd,
   int iPart,
   StringBuilder pszBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-sb_gettextw)
