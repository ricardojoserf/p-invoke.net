## DdeQueryString

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern uint DdeQueryStringA(IntPtr idInst,
   IntPtr hsz,
   StringBuilder psz,
   uint cchMax,
   int iCodePage
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddequerystringa)
