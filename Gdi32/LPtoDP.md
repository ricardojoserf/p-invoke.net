## LPtoDP

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool LPtoDP(
   IntPtr hdc,
   [In,
   Out] ref POINT lpPoints,
   int nCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-lptodp)
