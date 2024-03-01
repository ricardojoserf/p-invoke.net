## DdeEnableCallback

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeEnableCallback(
   IntPtr idInst,
   IntPtr hConv,
   uint wCmd
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddeenablecallback)
