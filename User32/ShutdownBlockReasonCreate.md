## ShutdownBlockReasonCreate

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool ShutdownBlockReasonCreate(
   IntPtr hWnd,
   string reason
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-shutdownblockreasoncreate)
