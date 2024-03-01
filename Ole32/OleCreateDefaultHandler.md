## OleCreateDefaultHandler

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreateDefaultHandler(
   ref Guid clsid,
   IUnknown pUnkOuter,
   ref Guid riid,
   out object lplpObj
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olecreatedefaulthandler)
