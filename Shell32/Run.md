## Run

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern uint Run(
   IntPtr hwnd,
   IntPtr hIcon,
   string lpszDir,
   string lpszCmd,
   string lpszArgs,
   int nShowCmd
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-runw)
