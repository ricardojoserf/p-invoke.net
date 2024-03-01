## GetDefaultPrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool GetDefaultPrinter(
   StringBuilder pszBuffer,
   ref uint pcchBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-getdefaultprintera)
