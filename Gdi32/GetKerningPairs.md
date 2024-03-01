## GetKerningPairs

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetKerningPairs(
   IntPtr hdc,
   uint nPairs,
   [Out] KERNINGPAIR[] lpkrnpair
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getkerningpairsa)
