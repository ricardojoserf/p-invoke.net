## ExtCreatePen

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr ExtCreatePen(
   uint iPenStyle,
   uint cWidth,
   IntPtr plbrush,
   uint cStyle,
   [In] uint[] lpstyle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-extcreatepen)
