## CreateIC

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreateIC(
   string lpszDriver,
   string lpszDevice,
   string lpszOutput,
   IntPtr lpInitData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createica)
