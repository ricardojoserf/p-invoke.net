## DPtoLP

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool DPtoLP(
   IntPtr hdc,
   [In,
   Out] ref POINT lpPoints,
   int nCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-dptolp)
