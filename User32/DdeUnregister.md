## DdeUnregister

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeUnregister(
   IntPtr idInst,
   IntPtr hsz,
   IntPtr hConv
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddeunregister)
