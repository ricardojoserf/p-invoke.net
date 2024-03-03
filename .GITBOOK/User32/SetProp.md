## SetProp

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetProp(
   IntPtr hWnd,
   string lpString,
   IntPtr hData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setpropw)
