## GetKeyNameText

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern int GetKeyNameText(
   uint lParam,
   StringBuilder lpString,
   int nSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getkeynametext)
