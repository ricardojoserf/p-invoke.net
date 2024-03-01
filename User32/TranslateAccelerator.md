## TranslateAccelerator

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int TranslateAccelerator(
   IntPtr hWnd,
   IntPtr hAccTable,
   ref MSG lpMsg
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-translateacceleratorw)
