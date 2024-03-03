## GetErrorInfo

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int GetErrorInfo(
   uint dwReserved,
   out IErrorInfo pperrinfo
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/oleauto/nf-oleauto-geterrorinfo)
