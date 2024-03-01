## SetWindowsHookEx

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr SetWindowsHookEx(
   int idHook,
   HookProc lpfn,
   IntPtr hmod,
   uint dwThreadId
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowshookexw)
