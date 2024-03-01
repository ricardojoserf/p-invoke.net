## GetAltTabInfo

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern bool GetAltTabInfoA(IntPtr hwnd,
   int iItem,
   ref ALTTABINFO pati,
   StringBuilder pszItemText,
   uint cchItemText
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getalttabinfoa)
