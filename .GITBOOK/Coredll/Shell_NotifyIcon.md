## Shell_NotifyIcon

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool Shell_NotifyIcon(
   uint dwMessage,
   ref NOTIFYICONDATA lpdata
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shell_notifyiconw)
