## GetClipboardFormatName

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern int GetClipboardFormatNameA(uint format,
   StringBuilder lpszFormatName,
   int cchMaxCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getclipboardformatnamea)
