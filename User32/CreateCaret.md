## CreateCaret

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateCaret(
   IntPtr hWnd,
   IntPtr hBitmap,
   int nWidth,
   int nHeight
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createcaret)
