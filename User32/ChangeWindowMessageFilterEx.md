## ChangeWindowMessageFilterEx

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ChangeWindowMessageFilterEx(
   IntPtr hwnd,
   uint message,
   uint action,
   IntPtr pChangeFilterStruct
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-changewindowmessagefilterex)
