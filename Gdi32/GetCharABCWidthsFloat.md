## GetCharABCWidthsFloat

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetCharABCWidthsFloat(
   IntPtr hdc,
   uint iFirst,
   uint iLast,
   [Out] ABCFLOAT[] lpABCF
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcharabcwidthsfloata)
