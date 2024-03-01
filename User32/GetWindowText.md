## GetWindowText

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int GetWindowText(
   IntPtr hWnd,
   [Out] StringBuilder lpString,
   int nMaxCount
);
```

Microsoft documentation: (TODO)
