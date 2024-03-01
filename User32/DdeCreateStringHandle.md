## DdeCreateStringHandle

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr DdeCreateStringHandle(
   IntPtr idInst,
   string psz,
   int iCodePage
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddecreatestringhandlea)
