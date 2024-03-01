## NOTIFYICONDATA

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool NOTIFYICONDATA(
   IntPtr hwnd,
   uint uID,
   uint uFlags,
   uint dwMessage,
   IntPtr hIcon,
   string szTip,
   uint dwState,
   uint dwStateMask,
   string szInfo,
   uint uTimeout,
   string szInfoTitle,
   uint dwInfoFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/ns-shellapi-notifyicondataw)
