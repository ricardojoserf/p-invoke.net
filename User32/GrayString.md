## GrayString

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool GrayString(
   IntPtr hdc,
   IntPtr hBrush,
   IntPtr lpOutputFunc,
   IntPtr lpData,
   int nCount,
   int x,
   int y,
   int nWidth,
   int nHeight
);
```

[Microsoft documentation](TODO)
