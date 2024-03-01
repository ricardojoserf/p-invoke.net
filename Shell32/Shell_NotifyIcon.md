## Shell_NotifyIcon

```
[DllImport("shell32.dll")]
public static extern bool Shell_NotifyIcon(
   uint dwMessage,
   ref NOTIFYICONDATA lpdata
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shell_notifyiconw)
