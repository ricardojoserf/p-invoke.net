## CallNextHookEx

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr CallNextHookEx(
   IntPtr hhk,
   int nCode,
   IntPtr wParam,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-callnexthookex)
