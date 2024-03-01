## SetClassLongPtr

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern UIntPtr SetClassLongPtr(
   IntPtr hWnd,
   int nIndex,
   UIntPtr dwNewLong
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setclasslongptrw)
