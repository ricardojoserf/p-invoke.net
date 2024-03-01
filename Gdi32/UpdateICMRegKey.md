## UpdateICMRegKey

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int UpdateICMRegKey(
   IntPtr reserved,
   string lpszCMID,
   string lpszFileName,
   uint command
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-updateicmregkeya)
