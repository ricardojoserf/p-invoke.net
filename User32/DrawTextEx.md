## DrawTextEx

```
[DllImport("user32.dll", SetLastError = true)]
public static extern int DrawTextExA(
   IntPtr hdc,
   string lpchText,
   int cchText,
   ref RECT lprc,
   uint dwDTFormat,
   ref DRAWTEXTPARAMS lpDTParams
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-drawtextexa)
