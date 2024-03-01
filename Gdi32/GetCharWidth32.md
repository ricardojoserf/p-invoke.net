## GetCharWidth32

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetCharWidth32(
   IntPtr hdc,
   uint iFirst,
   uint iLast,
   [Out] float[] lpBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharwidth32a)
