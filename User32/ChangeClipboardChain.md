## ChangeClipboardChain

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ChangeClipboardChain(
   IntPtr hWndRemove,
   IntPtr hWndNewNext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-changeclipboardchain)
