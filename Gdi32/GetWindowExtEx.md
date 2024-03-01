## GetWindowExtEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetWindowExtEx(
   IntPtr hdc,
   out SIZE lpSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getwindowextex)
