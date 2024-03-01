## ExpandEnvironmentStrings

```
[DllImport("kernel32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern uint ExpandEnvironmentStringsA(string lpSrc,
   StringBuilder lpDst,
   uint nSize
);
```

Microsoft documentation: (TODO)
