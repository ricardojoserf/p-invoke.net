## CreateItemMoniker

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateItemMoniker(
   string lpszDelim,
   string lpszItem,
   out IMoniker ppmk
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-createitemmoniker)
