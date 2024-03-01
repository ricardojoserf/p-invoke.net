## CombineRgn

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int CombineRgn(
   IntPtr hrgnDest,
   IntPtr hrgnSrc1,
   IntPtr hrgnSrc2,
   int fnCombineMode
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-combinergn)
