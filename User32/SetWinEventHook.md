## SetWinEventHook

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr SetWinEventHook(
   uint eventMin,
   uint eventMax,
   IntPtr hmodWinEventProc,
   WinEventProc pfnWinEventProc,
   uint idProcess,
   uint idThread,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwineventhook)
