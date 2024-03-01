## GetWindowModuleFileName

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern uint GetWindowModuleFileName(
   IntPtr hwnd,
   [Out] StringBuilder lpszFileName,
   uint cchFileNameMax
);
```

[Microsoft documentation](TODO)
