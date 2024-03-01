## ExpandEnvironmentStrings

```
[DllImport("kernel32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern uint ExpandEnvironmentStringsA(string lpSrc,
   StringBuilder lpDst,
   uint nSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-expandenvironmentstringsa)
