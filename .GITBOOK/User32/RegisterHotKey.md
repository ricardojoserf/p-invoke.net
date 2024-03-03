## RegisterHotKey

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool RegisterHotKey(
   IntPtr hWnd,
   int id,
   uint fsModifiers,
   uint vk
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-registerhotkey)
