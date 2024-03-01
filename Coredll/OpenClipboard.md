## OpenClipboard

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool OpenClipboard(
   IntPtr hWndNewOwner
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-openclipboard)
