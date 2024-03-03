## DdeCreateStringHandle

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr DdeCreateStringHandle(
   IntPtr idInst,
   string psz,
   int iCodePage
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddecreatestringhandlea)
