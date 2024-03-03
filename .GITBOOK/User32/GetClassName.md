## GetClassName

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern int GetClassNameA(IntPtr hWnd,
   StringBuilder lpClassName,
   int nMaxCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getclassnamea)
