## ShutdownBlockReasonQuery

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool ShutdownBlockReasonQuery(
   IntPtr hWnd,
   StringBuilder pwszReason,
   ref uint pcchReason
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-shutdownblockreasonquery)
