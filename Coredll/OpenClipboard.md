## OpenClipboard

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool OpenClipboard(
   IntPtr hWndNewOwner
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-openclipboard)
