## GetCharABCWidthsI

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetCharABCWidthsI(
   IntPtr hdc,
   uint giFirst,
   uint cgi,
   [In] IntPtr pgi,
   [Out] ABC[] lpABC
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharabcwidthsi)
