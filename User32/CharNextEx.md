## CharNextEx

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr CharNextEx(
   uint codePage,
   IntPtr lpCurrentChar,
   uint flags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-charnextexw)
