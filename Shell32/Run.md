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

[Microsoft documentation](TODO)
