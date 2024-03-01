## GetCharABCWidths

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetCharABCWidths(
   IntPtr hdc,
   uint wFirst,
   uint wLast,
   [Out] ABC[] lpABC
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharabcwidthsa)
