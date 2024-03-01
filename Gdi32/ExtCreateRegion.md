## ExtCreateRegion

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr ExtCreateRegion(
   [In] ref XFORM lpXform,
   uint nCount,
   [In] IntPtr lpRgnData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-extcreatergn)
