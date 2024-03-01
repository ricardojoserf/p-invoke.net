## SetBrushOrgEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetBrushOrgEx(
   IntPtr hdc,
   int nXOrg,
   int nYOrg,
   out POINT lppt
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setbrushorgex)
