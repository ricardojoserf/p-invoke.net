## BindMoniker

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int BindMoniker(
   IMoniker pmk,
   uint grfOpt,
   ref Guid iidResult,
   out object ppvResult
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/objidl/nf-objidl-ibindmoniker-bindmoniker)
