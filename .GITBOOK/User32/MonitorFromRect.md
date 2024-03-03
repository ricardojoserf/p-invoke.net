## MonitorFromRect

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr MonitorFromRect(
   ref RECT lprc,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-monitorfromrect)
