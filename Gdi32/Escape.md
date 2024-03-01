## Escape

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int Escape(
   IntPtr hdc,
   int iEscape,
   int cjIn,
   string lpIn,
   IntPtr lpOut
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-escape)
